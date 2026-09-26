<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wgpadacah"/><path clip-rule="evenodd" class="wxk8270ve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wgpadacah {
  d: path("M5.7022 11.7199L2.4363 9.4902C1.7402 9.015 1.9082 7.9446 2.7164 7.7054L22 2L20.7043 6.3794M18.5491 5.4509L22 2");
}

.wxk8270ve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 15.5C23 19.6421 19.6421 23 15.5 23C11.3579 23 8 19.6421 8 15.5C8 11.3579 11.3579 8 15.5 8C19.6421 8 23 11.3579 23 15.5ZM16.5 13C16.5 12.4477 16.0523 12 15.5 12C14.9477 12 14.5 12.4477 14.5 13L14.5 15.5C14.5 16.0523 14.9477 16.5 15.5 16.5L18 16.5C18.5523 16.5 19 16.0523 19 15.5C19 14.9477 18.5523 14.5 18 14.5L16.5 14.5L16.5 13Z");
  stroke: none;
}

</style>
