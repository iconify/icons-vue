<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wa_jyzbya"/><path class="a1_m7zbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-duotone-sharp" /></template>
<style>
.a1_m7zbdb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h10v7c0 .958-.106 1.855-.305 2.695m-1.952 4.048C16.3 18.59 14.279 19.987 12 21c-4.5-2-8-5.5-8-11V3M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.wa_jyzbya {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.743 16.743C16.254 18.648 14.192 20.025 12 21c-4.676-2.082-7.994-5.653-8-11V3ZM10 3h10v7a11.6 11.6 0 0 1-.305 2.695Z");
}

</style>
