<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dn99obbrv"/><path class="i6u1trbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:runtime" /></template>
<style>
.dn99obbrv {
  d: path("m10.036 4.123l.077-.399a1.32 1.32 0 0 1 1.298-1.074h1.178a1.32 1.32 0 0 1 1.298 1.074l.077.399a1.5 1.5 0 0 0 .723 1.018l1.909 1.103a1.5 1.5 0 0 0 1.244.117l.384-.134a1.32 1.32 0 0 1 1.579.588l.589 1.02a1.32 1.32 0 0 1-.281 1.661l-.308.266a1.5 1.5 0 0 0-.519 1.136v2.204a1.5 1.5 0 0 0 .519 1.136l.308.266a1.32 1.32 0 0 1 .281 1.661l-.589 1.02a1.32 1.32 0 0 1-1.579.588l-.384-.134a1.5 1.5 0 0 0-1.244.117l-1.909 1.103a1.5 1.5 0 0 0-.723 1.018l-.077.399a1.32 1.32 0 0 1-1.298 1.074h-1.178a1.32 1.32 0 0 1-1.298-1.074l-.077-.399a1.5 1.5 0 0 0-.723-1.018l-1.909-1.103a1.5 1.5 0 0 0-1.244-.117l-.384.134a1.32 1.32 0 0 1-1.579-.588l-.589-1.02a1.32 1.32 0 0 1 .281-1.661l.308-.266a1.5 1.5 0 0 0 .519-1.136v-2.204a1.5 1.5 0 0 0-.519-1.136l-.308-.266a1.32 1.32 0 0 1-.281-1.661l.589-1.02a1.32 1.32 0 0 1 1.579-.588l.384.134a1.5 1.5 0 0 0 1.244-.117l1.909-1.103a1.5 1.5 0 0 0 .723-1.018");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6u1trbdu {
  d: path("m12.417 9.641l1.411.869a1.75 1.75 0 0 1 0 2.98l-1.411.869a1.75 1.75 0 0 1-2.667-1.491v-1.736a1.75 1.75 0 0 1 2.667-1.491");
}

</style>
