<template>
    <div class="counter">
        <v-btn color="info" v-on:click="click">Click</v-btn>

        <h1>{{ count }}</h1>
    </div>
</template>

<script>
export default {
  name: "counter",
  data() {
    return {
      count: 0
    };
  },
  methods: {
    click: function() {
      this.count++;
    }
  }
};
</script>

<style>
</style>
