<template>
  <v-form>
    <v-container grid-list-xl>
      <v-layout wrap>

        <v-flex xs12 sm6>
          <v-text-field
            v-model="message1"
            label="Regular"
            clearable
          ></v-text-field>
        </v-flex>

        <v-flex xs12 sm6>
          <v-text-field
            v-model="message2"
            solo
            label="Solo"
            clearable
          ></v-text-field>
        </v-flex>

        <v-flex xs12 sm6>
          <v-text-field
            v-model="message3"
            filled
            label="Filled"
            clearable
          ></v-text-field>
        </v-flex>

        <v-flex xs12 sm6>
          <v-text-field
            v-model="message4"
            label="Outlined"
            outlined
            clearable
          ></v-text-field>
        </v-flex>

      </v-layout>
    </v-container>
  </v-form>
</template>

<script>
  export default {
    data () {
      return {
        message1: 'Hey!',
        message2: 'Hey!',
        message3: 'Hey!',
        message4: 'Hey!',
      }
    },
  }
</script>
