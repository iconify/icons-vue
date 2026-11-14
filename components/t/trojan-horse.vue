<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwwdd_b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trojan-horse" /></template>
<style>
.iwwdd_b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11H16v5.5H3.5Zm9.5 0l2.5-5.5l4-1.5l1 3.5l-3 1L16 11M6 16.5v4m3-4v4m3-4v4m3-4v4");
}

</style>
