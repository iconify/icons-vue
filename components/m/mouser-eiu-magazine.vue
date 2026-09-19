<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="r4hvhx12x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mouser-eiu-magazine" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.r4hvhx12x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.466 30.654V9.5L24 30.678L34.534 9.531v21.147M17.818 38.5h2.859m-2.859-5.719h2.859m-2.859 2.859h1.859m-1.859-2.859V38.5m5.724-5.719V38.5m2.923-5.72v3.79c0 1.072.858 1.93 1.859 1.93s1.858-.858 1.858-1.93v-3.79");
}

</style>
