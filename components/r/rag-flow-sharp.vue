<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2_5zmbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rag-flow-sharp" /></template>
<style>
.l2_5zmbok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h9v11h-9zm2.75 3.5H9m-3.5 3.5H9M13.5 7h3v3.5M15 9.25l1.5 1.5l1.5-1.5m-1.5 3.25q.51 3.74 4.25 4.25q-3.74.51-4.25 4.25q-.51-3.74-4.25-4.25q3.74-.51 4.25-4.25Z");
}

</style>
