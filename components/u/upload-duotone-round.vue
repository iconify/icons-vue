<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zltmsaboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upload-duotone-round" /></template>
<style>
.zltmsaboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 8l-4-4l-4 4m4-4v12m-8 0a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4");
}

</style>
