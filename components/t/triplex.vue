<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vvn1sznwd"/><path class="cwdtztbzg"/><path class="lribtcbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:triplex" /></template>
<style>
.cwdtztbzg {
  d: path("M5 6.75V21.5h14V6.75m-14 5h14M5 16.5h14M8.5 9.25h.01m6.99 0h.01m-7.01 5h.01m6.99 0h.01M8.5 19h.01");
}

.lribtcbfp {
  d: path("M11 21.5v-2.75h2v2.75m2.5-2.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvn1sznwd {
  d: path("m3.5 7.5l8.5-5l8.5 5");
}

</style>
