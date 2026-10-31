<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z_zygfbdd"/><path class="w7kufcb8h"/><path class="p6l9nfbfn"/><path class="jf-uovv_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jf-uovv_h {
  fill: currentColor;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6Z");
  stroke: none;
}

.p6l9nfbfn {
  d: path("M11 6L17 6");
}

.w7kufcb8h {
  fill: currentColor;
  d: path("M17 14C17 16.7614 14.7614 19 12 19C9.2386 19 7 16.7614 7 14C7 11.2386 9.2386 9 12 9C14.7614 9 17 11.2386 17 14Z");
  stroke: none;
}

.z_zygfbdd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
