<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jlw99p0bi"/><path class="gdw8tccwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-plus-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gdw8tccwx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h8v18l-4-2l-4 2l-4-2l-4 2V3zm-3 8h6m-3-3v6");
}

.jlw99p0bi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 3v18l-4-2l-4 2l-4-2l-4 2V3Z");
}

</style>
