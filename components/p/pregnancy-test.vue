<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xhb1j43tv"/><path class="k04ied38y"/><path class="nwzwk-bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pregnancy-test" /></template>
<style>
.k04ied38y {
  d: path("M10.25 10h3.5v5.5h-3.5Zm.5 8.25h2.5");
}

.nwzwk-bam {
  fill: currentColor;
  d: path("M19 15.5c1.25 1.5 2 2.5 2 3.5c0 1.25-.9 2-2 2s-2-.75-2-2c0-1 .75-2 2-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhb1j43tv {
  d: path("M8.5 2.5h7v19h-7Zm0 5h7");
}

</style>
