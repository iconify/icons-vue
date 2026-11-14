<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oe5y2u6sa"/><path class="vssxu60si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:viewing-appointment" /></template>
<style>
.oe5y2u6sa {
  d: path("M13.7 21.5H3.5v-17h17v8.9M8 2.5v4m8-4v4M3.5 9h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vssxu60si {
  d: path("M14.25 18c2-3 5.5-3 7.5 0c-2 3-5.5 3-7.5 0ZM18 18h.01");
}

</style>
