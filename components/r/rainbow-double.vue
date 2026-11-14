<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xpnq25_jo"/><path class="glc9pkbtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rainbow-double" /></template>
<style>
.glc9pkbtm {
  d: path("M6.25 16.5a5.75 5.75 0 0 1 11.5 0m-15.25 0h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpnq25_jo {
  d: path("M2.5 16.5a9.5 9.5 0 0 1 19 0");
}

</style>
