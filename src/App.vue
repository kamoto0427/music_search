<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <span>MUSIC SEARCH</span>
      <div class="d-flex align-center">
        <v-img
          class="shrink mr-2"
          contain
          transition="scale-transition"
          width="40"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Home</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
