<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk51p2b_k"/><path class="yl-m5bb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-disabled-by-default" /></template>
<style>
.vk51p2b_k {
  fill: currentColor;
  d: path("M5 5v14h14V5zm12 10.59L15.59 17L12 13.41L8.41 17L7 15.59L10.59 12L7 8.41L8.41 7L12 10.59L15.59 7L17 8.41L13.41 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yl-m5bb0o {
  fill: currentColor;
  d: path("M19 19H5V5h14zM3 3v18h18V3zm14 12.59L15.59 17L12 13.41L8.41 17L7 15.59L10.59 12L7 8.41L8.41 7L12 10.59L15.59 7L17 8.41L13.41 12z");
}

</style>
