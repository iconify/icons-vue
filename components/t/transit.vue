<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mi3eoweil"/><ellipse class="j2-wlnbhs"/><ellipse class="uqbuj_z8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transit" /></template>
<style>
.j2-wlnbhs {
  cx: 8.446px;
  cy: 21.708px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.946px;
  ry: 3.955px;
}

.mi3eoweil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.446 7.63v6.961M39.554 40.37v-7.165m0-14.234v-3.549a7.777 7.777 0 1 0-15.554 0v17.156a7.777 7.777 0 1 1-15.554 0v-3.753");
}

.uqbuj_z8n {
  cx: 39.554px;
  cy: 26.088px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.946px;
  ry: 3.955px;
}

</style>
