<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hfxqweb6k"/><path class="a97dvlbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:purchase-agreement" /></template>
<style>
.a97dvlbly {
  d: path("M7 15c1-2 2-2 2.5 0c.5 1.5 1.5 1.5 2.5-.5m-5.5 3h4.8m3.45.5l2 2L21 15.75");
}

.hfxqweb6k {
  d: path("M14.3 21.5H3.5v-19h15v11.8M7 6.5h8M7 10h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
