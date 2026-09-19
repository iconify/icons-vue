<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1iuo5w5u"/><path class="ig8yanb_h"/><path class="nbd71l8pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tarnhelm" /></template>
<style>
.e1iuo5w5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27 26h7.25c4.57 0 8.25 3.68 8.25 8.25s-3.68 8.25-8.25 8.25H27m-6 0h-7.25c-4.57 0-8.25-3.68-8.25-8.25S9.18 26 13.75 26H21");
}

.ig8yanb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.818 26.008A6.5 6.5 0 0 1 17.5 24a6.5 6.5 0 0 1 6.5-6.5a6.5 6.5 0 0 1 6.5 6.5a6.5 6.5 0 0 1-.318 2.008m1.068 8.242h-14.5");
}

.nbd71l8pj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.746 26.564a13.5 13.5 0 0 1-.064-4.77L5.854 18.43l4.25-7.36l5.328 2.498a13.5 13.5 0 0 1 3.818-2.205l.5-5.863h8.5l.5 5.863a13.5 13.5 0 0 1 3.82 2.205l5.327-2.499l4.25 7.361l-4.828 3.365c.12.729.181 1.466.181 2.266s-.082 1.658-.246 2.503");
}

</style>
