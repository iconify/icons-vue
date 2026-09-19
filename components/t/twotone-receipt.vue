<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag7ji1bjt"/><path class="l1-tk2boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-receipt" /></template>
<style>
.ag7ji1bjt {
  fill: currentColor;
  d: path("M5 19.09h14V4.91H5zM6 7h12v2H6zm0 4h12v2H6zm0 4h12v2H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.l1-tk2boy {
  fill: currentColor;
  d: path("M19.5 3.5L18 2l-1.5 1.5L15 2l-1.5 1.5L12 2l-1.5 1.5L9 2L7.5 3.5L6 2L4.5 3.5L3 2v20l1.5-1.5L6 22l1.5-1.5L9 22l1.5-1.5L12 22l1.5-1.5L15 22l1.5-1.5L18 22l1.5-1.5L21 22V2zM19 19.09H5V4.91h14zM6 15h12v2H6zm0-4h12v2H6zm0-4h12v2H6z");
}

</style>
