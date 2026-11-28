<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cqom7uzef"/><path class="lk0qgtdfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-code-sharp-duotone" /></template>
<style>
.cqom7uzef {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lk0qgtdfu {
  d: path("M10.2929 7.2071L10 7.5L7.5 10L10 12.5L10.2929 12.7929M13.7071 7.2071L14 7.5L16.5 10L14 12.5L13.7071 12.7929");
}

</style>
