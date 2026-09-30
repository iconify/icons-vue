<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aq4podvjp"/><path class="ij90-erqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stamp-two-tone" /></template>
<style>
.aq4podvjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.1092 8.5165L15.769 11L17 11C19.7614 11 22 13.2386 22 16C22 17.1046 21.1046 18 20 18L4 18C2.8954 18 2 17.1046 2 16C2 13.2386 4.2386 11 7 11L8.231 11L8.8908 8.5165C8.3145 7.8044 8 6.9161 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6C16 6.9161 15.6855 7.8044 15.1092 8.5165Z");
  stroke: none;
}

.ij90-erqw {
  d: path("M14 8.2361L14.8025 11.2568C14.919 11.695 15.3156 12 15.769 12L17 12C19.2091 12 21 13.7909 21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16C3 13.7909 4.7909 12 7 12L8.231 12C8.6844 12 9.081 11.695 9.1975 11.2568L10 8.2361C9.3637 7.6669 9 6.8537 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6C15 6.8537 14.6363 7.6669 14 8.2361ZM5 21L19 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
