<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyf3p5f3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:safepal" /></template>
<style>
.fyf3p5f3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.666 30.71V14.991h17.681l9.166-8.505H19.905L5.5 20.892zm18.668-13.42v15.718H15.653l-9.166 8.505h21.608L42.5 27.108z");
}

</style>
