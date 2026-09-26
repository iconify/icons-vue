<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bu1ghwbvs"/><path class="u3r-okbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock-two-tone" /></template>
<style>
.bu1ghwbvs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 15.5C23 19.6421 19.6421 23 15.5 23C11.3579 23 8 19.6421 8 15.5C8 11.3579 11.3579 8 15.5 8C19.6421 8 23 11.3579 23 15.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u3r-okbav {
  d: path("M5.7022 11.7199L2.4363 9.4902C1.7402 9.015 1.9082 7.9446 2.7164 7.7054L22 2L20.7043 6.3794M18.5491 5.4509L22 2M22 15.5C22 19.0899 19.0899 22 15.5 22C11.9101 22 9 19.0899 9 15.5C9 11.9101 11.9101 9 15.5 9C19.0899 9 22 11.9101 22 15.5ZM15.5 13L15.5 15.5L18 15.5");
}

</style>
