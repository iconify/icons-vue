<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lrqx-kbjc"/><path class="bnn48h5ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patent-gear" /></template>
<style>
.bnn48h5ln {
  d: path("m11.474 6.806l.06-1.025h.932l.06 1.025l.83.344l.767-.682l.659.659l-.682.767l.344.83l1.025.06v.932l-1.025.06l-.344.83l.682.767l-.659.659l-.767-.682l-.83.344l-.06 1.025h-.932l-.06-1.025l-.83-.344l-.767.682l-.659-.659l.682-.767l-.344-.83l-1.025-.06v-.932l1.025-.06l.344-.83l-.682-.767l.659-.659l.767.682Z");
}

.lrqx-kbjc {
  d: path("M9 18v-2.5C6.75 14 5.25 11.75 5.25 9.25a6.75 6.75 0 0 1 13.5 0c0 2.5-1.5 4.75-3.75 6.25V18Zm1.25 3h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
