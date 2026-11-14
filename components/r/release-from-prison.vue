<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6gcd3-qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:release-from-prison" /></template>
<style>
.j6gcd3-qk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 3.5h-10a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2h10m-8.25-17v17M10 3.5v17m2.75-8.5h8.75m-3-3l3 3l-3 3");
}

</style>
