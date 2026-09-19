<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nr5m2jq6k"/><circle class="s7xy_cope"/><path class="yy_ezikcy"/><path class="jnf6plaqi"/><path class="whnx8fbml"/><circle class="b-s60abkp"/><path class="ht-3qbbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pantip" /></template>
<style>
.b-s60abkp {
  cx: 28.836px;
  cy: 16.971px;
  r: 0.75px;
  fill: currentColor;
}

.ht-3qbbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.611 15.318c-1.308-.165-1.773.392-1.773.392");
}

.jnf6plaqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.008c6.149 0 11.307 4.986 11.133 11.133c-.245 8.651-.413 14.06-.525 17.39c-.114 3.396-.5 5.461-2.07 5.461s-1.963-2.378-2.106-5.293c-2.232-.27-4.823-.385-6.432-.385s-4.2.115-6.432.385c-.143 2.915-.535 5.293-2.106 5.293s-1.956-2.065-2.07-5.46c-.112-3.33-.28-8.74-.525-17.391C12.693 11.993 17.851 7.007 24 7.007");
}

.nr5m2jq6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.568 35.699c-1.484 3.093-3.67 5.4-5.243 4.58s.942-6.747.942-6.747m.482-12.952s-8.46.746-8.245 2.491c.214 1.745 5.871 2.074 8.548 1.931c-5.818-1.481-6.094-7.388-4.872-7.897c.857-.357.893 2.891 4.569 3.476");
}

.s7xy_cope {
  cx: 19.164px;
  cy: 16.971px;
  r: 0.75px;
  fill: currentColor;
}

.whnx8fbml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.432 35.699c1.484 3.093 3.67 5.4 5.243 4.58s-.942-6.747-.942-6.747m-.482-12.952s8.46.746 8.245 2.491s-5.871 2.074-8.548 1.931c5.818-1.481 6.094-7.388 4.872-7.897c-.857-.357-.893 2.891-4.569 3.476M24 21.528c1.016 0 1.941-.342 2.637-1.484c0 0-1.464-.408-2.635-.408h-.004c-1.171 0-2.635.408-2.635.408c.66 1.158 1.62 1.484 2.637 1.484");
}

.yy_ezikcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.389 15.318c1.308-.165 1.773.392 1.773.392");
}

</style>
