<template>
  <v-app>
    <v-main>
      <MenuPrincipal/>
    </v-main>
    <router-view>

    </router-view>
  </v-app>
</template>

<script>
import MenuPrincipal from './components/MenuPrincipal';
/* import ElementosAll from './components/ElementosAll';
import BotonesAll from './components/BotonesAll'; */

export default {
  name: 'App',
  components: {
    MenuPrincipal,
    /* ElementosAll,
    BotonesAll, */
  },

  data: () => ({
    //
  }),
};
</script>
