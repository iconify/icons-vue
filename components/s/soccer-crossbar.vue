<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uerxt6beh"/><path class="aa-dyjbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-crossbar" /></template>
<style>
.aa-dyjbmm {
  d: path("M8.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM12 8h.01");
}

.uerxt6beh {
  d: path("M3.5 20.5v-16h17v16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
