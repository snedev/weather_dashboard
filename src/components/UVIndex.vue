<template>
  <div id="uvIndex">
    <p>UV Index: {{ uvIndex }}</p>
  </div>
</template>

<script>

export default {
  props: ["highlights"],
  data () {
    return {
      uvIndex: this.highlights.uvIndex.toString()
    }
  },
  methods: {

  },
  computed: {

  },
}
</script>

<style>

</style>
