<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gvzsybb0s"/><path clip-rule="evenodd" class="prbod8bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-plus-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gvzsybb0s {
  d: path("M12 21H3V3H21V12M11 8H17M18 14V22M14 18H22");
}

.prbod8bku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 8C9 8.552 8.552 9 8 9C7.448 9 7 8.552 7 8C7 7.448 7.448 7 8 7C8.552 7 9 7.448 9 8ZM9 12C9 12.552 8.552 13 8 13C7.448 13 7 12.552 7 12C7 11.448 7.448 11 8 11C8.552 11 9 11.448 9 12ZM9 16C9 16.552 8.552 17 8 17C7.448 17 7 16.552 7 16C7 15.448 7.448 15 8 15C8.552 15 9 15.448 9 16Z");
  stroke: none;
}

</style>
