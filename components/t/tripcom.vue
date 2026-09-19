<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="xd_pobuoo"/><circle class="o-lr__gog"/><path class="uhftlef-f"/><circle class="v6742bhrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tripcom" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.o-lr__gog {
  cx: 24.448px;
  cy: 15.73px;
  r: 0.75px;
  fill: currentColor;
}

.uhftlef-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.448 19.777v8.753m-6.194-5.45a3.303 3.303 0 0 1 3.303-3.303h0m-3.303-.001v8.754M9.5 15.317h8.754m-4.377 13.214V15.316");
}

.v6742bhrz {
  cx: 37.155px;
  cy: 27.185px;
  r: 1.345px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xd_pobuoo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.354 25.228a3.303 3.303 0 0 0 3.303 3.303h0a3.304 3.304 0 0 0 3.303-3.303V23.08a3.304 3.304 0 0 0-3.303-3.303h0a3.303 3.303 0 0 0-3.303 3.303m0-3.303V32.99");
}

</style>
