<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y5gb3nrnc"/><path class="j9l9hmerx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j9l9hmerx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h8v5M9 20H4V4h8M4 9h16M4 15h5m3-11v5m1 7h8");
}

.y5gb3nrnc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 3a1 1 0 0 1 1 1v5H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

</style>
