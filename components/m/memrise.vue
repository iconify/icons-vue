<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oo1wyqbwr"/><circle class="bk6jobc1z"/><path class="p7aohkjhz"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:memrise" /></template>
<style>
.bk6jobc1z {
  cx: 20.25px;
  cy: 25.27px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.oo1wyqbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.158 35.62H37.5m-5.342-10.684H37.5m-5.342 5.342h3.483m-3.483-5.342V35.62M21.81 21.384h4.507M21.81 12.37h4.507m-4.507 4.507h2.938M21.81 12.37v9.014m-11.31-.01V12.37l4.507 9.014l4.507-9.001v9.001m8.972-.01V12.37l4.507 9.014l4.507-9.001v9.001m-27 14.236V24.935h3.498a3.588 3.588 0 0 1 0 7.177H10.5m3.498 0l3.498 3.506");
}

.p7aohkjhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.25 28.542v7.078m2.672-1.17a2.99 2.99 0 0 0 2.62 1.17h1.582a2.67 2.67 0 0 0 2.665-2.67a2.67 2.67 0 0 0-2.665-2.672h-1.748a2.67 2.67 0 0 1-2.665-2.671a2.67 2.67 0 0 1 2.665-2.671h1.582a2.99 2.99 0 0 1 2.62 1.17");
}

</style>
