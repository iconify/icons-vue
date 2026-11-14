<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2o3dllyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-garden-centre" /></template>
<style>
.e2o3dllyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.5h13l-2 9h-9Zm.5 3h12m-6-3v-8M12 9c0-3.5-2.5-6-6.5-6C5.5 6.5 8 9 12 9Zm0 0c0-3.5 2.5-6 6.5-6c0 3.5-2.5 6-6.5 6Z");
}

</style>
