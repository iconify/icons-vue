<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hde0-jbzg"/><path class="q_dh2x6if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hde0-jbzg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.963 19.876c-1.802-1.661-3.349-3.669-4.226-5.974A10.9 10.9 0 0 1 4 10a7.98 7.98 0 0 1 2.343-5.657A7.98 7.98 0 0 1 12 2a7.98 7.98 0 0 1 5.657 2.343A7.98 7.98 0 0 1 20 10c-.001 3.878-2.192 7.322-4.963 9.876a20 20 0 0 1-2.482 1.956a1 1 0 0 1-1.11 0a20 20 0 0 1-2.482-1.956");
}

.q_dh2x6if {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 16c-1.424 2.15-3.346 3.897-5 5c-3-2-7-6-7-11c0-1.678 1.015-2.794 2-4m3-3c.566-.148 1.387 0 2 0a7 7 0 0 1 7 7c0 .624.115 1.41 0 2M3 2l19 19");
}

</style>
