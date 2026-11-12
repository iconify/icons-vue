<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os4ftrb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-warning-corner" /></template>
<style>
.os4ftrb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8V6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2M8 20H5a2 2 0 0 1-2-2V8m0 0h18m-4 6v4m0 3h.01");
}

</style>
