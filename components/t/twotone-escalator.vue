<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5d0e72cu"/><path class="w5mdk-7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-escalator" /></template>
<style>
.f5d0e72cu {
  fill: currentColor;
  d: path("M19 5v14H5V5zm-2 1h-3.3l-5 9H7c-.83 0-1.5.67-1.5 1.5S6.17 18 7 18h3.3l5-9H17c.83 0 1.5-.67 1.5-1.5S17.83 6 17 6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.w5mdk-7on {
  fill: currentColor;
  d: path("M19 5v14H5V5zm0-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-2 3h-3.3l-5 9H7c-.83 0-1.5.67-1.5 1.5S6.17 18 7 18h3.3l5-9H17c.83 0 1.5-.67 1.5-1.5S17.83 6 17 6");
}

</style>
