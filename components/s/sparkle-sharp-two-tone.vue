<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rjbz5rbai"/><path class="o2zxpdeiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2zxpdeiy {
  d: path("M12 3L14.7896 9.2104L21 12L14.7896 14.7896L12 21L9.2104 14.7896L3 12L9.2104 9.2104L12 3Z");
}

.rjbz5rbai {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.9122 2.5903L15.5461 8.4539L21.4097 11.0878C21.7689 11.2491 22 11.6062 22 12C22 12.3938 21.7689 12.7509 21.4097 12.9122L15.5461 15.5461L12.9122 21.4097C12.7509 21.7689 12.3938 22 12 22C11.6062 22 11.2491 21.7689 11.0878 21.4097L8.4539 15.5461L2.5903 12.9122C2.2311 12.7509 2 12.3938 2 12C2 11.6062 2.2311 11.2491 2.5903 11.0878L8.4539 8.4539L11.0878 2.5903C11.2491 2.2311 11.6062 2 12 2C12.3938 2 12.7509 2.2311 12.9122 2.5903Z");
  stroke: none;
}

</style>
