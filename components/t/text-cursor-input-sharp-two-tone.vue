<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p4lml4jpq"/><path class="qavogbdaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-cursor-input-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4lml4jpq {
  stroke-opacity: 0.4;
  d: path("M13 7L2 7L2 17L13 17M19 7L22 7L22 17L19 17");
}

.qavogbdaf {
  d: path("M16 4.25C15.5556 3.6875 14.1333 2 12 2L11 2M16 4.25C16.4444 3.6875 17.8667 2 20 2L21 2M16 4.25L16 19.75M16 19.75C16.4444 20.3125 17.8667 22 20 22L21 22M16 19.75C15.5556 20.3125 14.1333 22 12 22L11 22");
}

</style>
