<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zbu6bdv-x"/><path class="pvvxjrbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pvvxjrbrh {
  d: path("m16.5 10.875l3.947 1.974a1 1 0 0 1 .553.894v4.389a1 1 0 0 1-.553.894l-3.5 1.75a1 1 0 0 1-.894 0L12 18.75l-4.053 2.026a1 1 0 0 1-.894 0l-3.5-1.75A1 1 0 0 1 3 18.132v-4.389a1 1 0 0 1 .553-.894L7.5 10.875V5.868a1 1 0 0 1 .553-.894l3.5-1.75a1 1 0 0 1 .894 0l3.5 1.75a1 1 0 0 1 .553.894z");
}

.zbu6bdv-x {
  stroke-opacity: 0.4;
  d: path("M7.658 5.329L12 7.5l4.342-2.171M12 7.5v5.625m-4.5-2.25l4.5 2.25l4.5-2.25M3.158 13.204L7.5 15.375l4.5-2.25l4.5 2.25l4.342-2.171M7.5 15.375v5.507m4.5-7.757v5.625m4.5-3.375v5.507");
}

</style>
