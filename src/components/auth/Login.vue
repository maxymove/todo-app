<template>
  <v-app
    ><div>
      <v-card width="500" class="mx-auto mt-5">
        <v-card-title>Login Form</v-card-title>
        <v-card-text>
          <v-form>
            <v-text-field label="email" v-model="email"></v-text-field>
            <v-text-field label="password" v-model="password"></v-text-field>
            <div class="d-flex justify-space-between mb-6">
              <v-btn depressed elevation="2">login</v-btn>
              <v-btn depressed elevation="2">register</v-btn>
            </div>
          </v-form>
        </v-card-text>
        <v-card-actions> </v-card-actions>
      </v-card></div
  ></v-app>
</template>

<script>
export default {}
</script>

<style>
</style>
