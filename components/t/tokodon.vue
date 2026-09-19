<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l39cgxf6v"/><path class="vqpvmwboy"/><ellipse transform="rotate(-30 19.637 13.891)" class="u7orl--0o"/><ellipse transform="rotate(-60 27.812 13.886)" class="of2b_xbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tokodon" /></template>
<style>
.l39cgxf6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 7.498h25.5c2.77 0 5 2.23 5 5v4.5c0 1.385-1.115 2.5-2.5 2.5H12.5c-2.77 0-5-2.23-5-5v-4.5c0-1.385 1.115-2.5 2.5-2.5m8 12c.25 9.25 1.636 18.26 11 20.81c2.54.68 5-.5 8-2.5c2.25 2.25 3.25 0 1.25-1.5c.75-3.25-2.25-2.75-1.75-.5c-5.5 4.5-8.75-3.306-7.5-16.31");
}

.of2b_xbub {
  cx: 27.811px;
  cy: 13.886px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 1.5px;
}

.u7orl--0o {
  cx: 19.637px;
  cy: 13.891px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 2px;
}

.vqpvmwboy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32 19.498c-1.25 4 1 7 6 9.5c-1.25 1-7 .5-9.247-5.567M16 19.498c0 4.5-2 7.5-6 9.5c4.5 1 6-1.5 8.26-4.23");
}

</style>
