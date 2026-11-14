<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oi48jlbdw"/><path class="nqd_99bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paper-towel" /></template>
<style>
.nqd_99bcy {
  d: path("M5.5 2.5h13a2.5 4.5 0 0 1 0 9h-13m4 0v9l2-1l2 1.5l2-1.5l2 1.5v-9.5");
}

.oi48jlbdw {
  d: path("M3 7a2.5 4.5 0 1 0 5 0a2.5 4.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
