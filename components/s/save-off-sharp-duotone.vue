<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gg5yspjzh"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gg5yspjzh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M14.8715 14.8715L21.7071 21.7071C21.5198 21.8949 21.2653 22.0003 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C1.9997 2.7347 2.1051 2.4802 2.2929 2.2929L11.1285 11.1285C9.8642 11.5125 8.9998 12.6783 8.9998 13.9996C8.9998 15.6568 10.3432 17.0002 12.0004 17.0002C13.3217 17.0002 14.4875 16.1358 14.8715 14.8715ZM5.6569 2L17 2C17.2652 2 17.5196 2.1054 17.7071 2.2929L21.7071 6.2929C21.8946 6.4804 22 6.7348 22 7L22 18.3431L5.6569 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
