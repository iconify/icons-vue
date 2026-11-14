<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujnmxya1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:support-dashboard" /></template>
<style>
.ujnmxya1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h8V13h-8Zm0 13.5h8v5.5h-8Zm11-13.5h8V10h-8Zm1 15.5a3.25 3.25 0 0 1 6.5 0m-7.5 0h2v3.5h-2Zm6.5 0h2v3.5h-2Z");
}

</style>
