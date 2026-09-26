<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jw8qqub9q"/><path clip-rule="evenodd" class="pe14vrbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jw8qqub9q {
  d: path("M6.5744 11.0404L6.1382 10.7426L2 7.9174L22 2L20.7043 6.3794L20.4923 7.0957M18.2562 5.7438L18.5491 5.4509L22 2");
}

.pe14vrbci {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 15.5C23 19.6421 19.6421 23 15.5 23C11.3579 23 8 19.6421 8 15.5C8 11.3579 11.3579 8 15.5 8C19.6421 8 23 11.3579 23 15.5ZM16.5 12L14.5 12L14.5 15.5C14.5 16.0523 14.9477 16.5 15.5 16.5L19 16.5L19 14.5L16.5 14.5L16.5 12Z");
  stroke: none;
}

</style>
