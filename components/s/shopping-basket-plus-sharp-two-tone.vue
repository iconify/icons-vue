<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jcfycjb4c"/><path class="rtpw0fbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-basket-plus-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jcfycjb4c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 22L5 22C4.549 22 4.1539 21.6982 4.0352 21.2631L1.0353 10.2631C1.0119 10.1774 1 10.0889 1 10C1 9.4477 1.4478 9 2.0001 9L21.9999 9C22.5522 9 22.9999 9.4477 22.9999 10C22.9999 10.0889 22.9881 10.1774 22.9647 10.2631L22.491 12L13 12L13 22Z");
  stroke: none;
}

.rtpw0fbpc {
  d: path("M13 21L5 21L2.0001 10L21.9999 10L21.5262 11.7369M9 10L10 3L16 3L15 10M19 14L19 22M15 18L23 18");
}

</style>
