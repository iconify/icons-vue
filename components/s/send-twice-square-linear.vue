<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cit_55o-r"/><path class="t1_7z3t8t"/><path class="fp2x79bfq"/><path class="xvjk-cbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-twice-square-linear" /></template>
<style>
.cit_55o-r {
  stroke-linejoin: round;
  d: path("M17 15.5L10 15.5M13 18L10 15.5L13 13");
}

.fp2x79bfq {
  d: path("M6.99994 6.00024V18.0002");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1_7z3t8t {
  stroke-linejoin: round;
  d: path("M17.0001 8.49976L10.0001 8.49976M13.0001 10.9998L10.0001 8.49976L13.0001 5.99976");
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
