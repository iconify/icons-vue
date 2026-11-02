<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrgcr2bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation" /></template>
<style>
.xrgcr2bws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 2c1.107.369 1.738 1.631 1 2l-6 3l-3 6c-.369.738-1.631.107-2-1L4 6c-.412-1.236.764-2.412 2-2z");
}

</style>
