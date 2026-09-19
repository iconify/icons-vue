<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="phabijfgl"/><path class="d49golndp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:turk-telekom" /></template>
<style>
.d49golndp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.257 25.684l12.637 7.295V18.388zm31.488-14.173l-6.88-3.972v7.944z");
}

.phabijfgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.684L17.905 10.906v29.555zm-25.595-7.715L4.5 10.229v15.479z");
}

</style>
