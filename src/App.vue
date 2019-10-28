<template>
  <v-app>
    <AppBar />
    <v-content>
      <HelloWorld/>
    </v-content>
    <BottomBar />
  </v-app>
</template>

<script>
import AppBar from './components/Appbar';
import HelloWorld from './components/HelloWorld';
import BottomBar from './components/BottomBar';

export default {
  name: 'App',
  components: {
    HelloWorld,
    AppBar,
    BottomBar
  },
  data: () => ({
    //
  }),
};
</script>
