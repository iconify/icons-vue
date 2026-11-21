<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqqkfekik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-scan-sharp" /></template>
<style>
.zqqkfekik {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13V3H21V13M3 6L11.36361 8.84948C11.74386 9.05015 12.25614 9.05015 12.63639 8.84948L21 6M1 13H23M2 17H11M22 17H13M21 21H17M15 21H9M7 21H3");
}

</style>
