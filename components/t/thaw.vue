<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neqpo3bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thaw" /></template>
<style>
.neqpo3bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3v12m5.196-9L3.804 12m10.392 0L3.804 6M17.5 13.5s-2.5 3-2.5 5a2.5 2.5 0 0 0 5 0c0-2-2.5-5-2.5-5Z");
}

</style>
