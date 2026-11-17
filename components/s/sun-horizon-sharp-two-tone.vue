<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ihkjvvb5j"/><path class="r7edl5mfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-horizon-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ihkjvvb5j {
  stroke-opacity: 0.4;
  d: path("M3 19H21");
}

.r7edl5mfg {
  d: path("M7.5 16V15C7.5 12.515 9.515 10.5 12 10.5C14.485 10.5 16.5 12.515 16.5 15V16M1 15H4.5M19.5 15H23M4.636 7.636L6.282 9.283M19.364 7.636L17.718 9.283M12 7.5V4");
}

</style>
