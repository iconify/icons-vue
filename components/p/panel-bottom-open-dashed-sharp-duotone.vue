<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ozix77-sy"/><path class="sl9uo94_w"/><path class="f4kpv4bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open-dashed-sharp-duotone" /></template>
<style>
.f4kpv4bkd {
  d: path("M8.7071 11.2929L12 8L15.2929 11.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozix77-sy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14L21 14C21.5523 14 22 14.4477 22 15L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 15C2 14.4477 2.4477 14 3 14Z");
  stroke: none;
}

.sl9uo94_w {
  d: path("M7 3L3 3L3 7M21 7L21 3L17 3M3 9L3 12M21 9L21 12M9.5 3L14.5 3");
}

</style>
