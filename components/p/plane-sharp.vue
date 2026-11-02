<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq5y__wvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-sharp" /></template>
<style>
.uq5y__wvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 8l-3 3l2 8l-2 2l-4-6l-3 2v3l-1 1l-2-3l-3-2l1-1h3l2-3l-6-4l2-2l8 2l3-3c2-2 3-2 4-1s1 2-1 4");
}

</style>
