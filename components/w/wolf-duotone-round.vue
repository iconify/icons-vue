<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jhyhjl9to"/><path class="de60b-sok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-duotone-round" /></template>
<style>
.de60b-sok {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m21 11l-2 2l2 2l-5 2l-1 2c-.613 1.226-1.774 2-3 2s-2.387-.774-3-2l-1-2l-5-2l2-2l-2-2l1-1c.64-.64 1-1.72 1-3V5c0-.738.631-1.369 1-1l2 2c.64.64 1.72 1 3 1h2c1.28 0 2.36-.36 3-1l2-2c.369-.369 1 .262 1 1v2c0 1.28.36 2.36 1 3zM9 11l1 1m5-1l-1 1m-2 6h.01");
}

.ft5dv1b6b {
  fill: none;
}

.jhyhjl9to {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m21 15l-5 2l-1 2c-.569 1.137-1.695 1.999-3 2c-1.305-.001-2.431-.863-3-2l-1-2l-5-2l2-2l-2-2l1-1c.763-.764 1-1.959 1-3V5c0-.738.631-1.369 1-1l2 2c.764.763 1.959 1 3 1h2c1.041 0 2.236-.237 3-1l2-2c.369-.369 1 .262 1 1v2c0 1.041.237 2.236 1 3l1 1l-2 2Z");
}

</style>
