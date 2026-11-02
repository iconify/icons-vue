<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j639pfotf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:path-round" /></template>
<style>
.j639pfotf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.121 15.879L15.88 8.12M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
