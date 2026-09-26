<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b56cl7uxt"/><path clip-rule="evenodd" class="v-qjy5b7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-basket-sharp-fill" /></template>
<style>
.b56cl7uxt {
  d: path("M9 10L10 3L16 3L15 10");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-qjy5b7r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.0001 9L21.9999 9C22.5522 9 22.9999 9.4477 22.9999 10C22.9999 10.0889 22.9881 10.1774 22.9647 10.2631L19.9648 21.2631C19.8461 21.6982 19.451 22 19 22L5 22C4.549 22 4.1539 21.6982 4.0352 21.2631L1.0353 10.2631C1.0119 10.1774 1 10.0889 1 10C1 9.4477 1.4478 9 2.0001 9Z");
  stroke: none;
}

</style>
