<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l4t4idbxp"/><path class="b40fq7hzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spell-check-sharp-two-tone" /></template>
<style>
.b40fq7hzy {
  d: path("M15.7071 16.7071L18 19L22.2929 14.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l4t4idbxp {
  stroke-opacity: 0.4;
  d: path("M5 9C6.6569 9 8 10.3431 8 12C8 13.6569 6.6569 15 5 15C3.3431 15 2 13.6569 2 12C2 10.3431 3.3431 9 5 9ZM8 8L8 16M12 4L12 16M12 12C12 10.3431 13.3431 9 15 9C16.6569 9 18 10.3431 18 12C18 12.3407 17.942 12.6788 17.8284 13L17.5927 13.6667");
}

</style>
