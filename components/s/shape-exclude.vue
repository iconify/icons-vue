<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3uzs_b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shape-exclude" /></template>
<style>
.k3uzs_b0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h8.5a2 2 0 0 1 2 2V6a1 1 0 0 1-1 1H9a2 2 0 0 0-2 2v5.25a1 1 0 0 1-1 1H4.75a2 2 0 0 1-2-2v-8.5a2 2 0 0 1 2-2m14.5 18.5h-8.5a2 2 0 0 1-2-2V18a1 1 0 0 1 1-1H15a2 2 0 0 0 2-2V9.75a1 1 0 0 1 1-1h1.25a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2");
}

</style>
