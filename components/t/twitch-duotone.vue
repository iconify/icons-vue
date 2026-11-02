<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j20pehbum"/><path class="a6l6oduar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:twitch-duotone" /></template>
<style>
.a6l6oduar {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7v4m4-4v4M4 3h16v10l-4 4h-4l-4 4v-4H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.j20pehbum {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 2a1 1 0 0 1 1 1v10c0 .265-.105.52-.293.707l-4 4A1 1 0 0 1 16 18h-3.586l-3.707 3.707A1 1 0 0 1 7 21v-3H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>
