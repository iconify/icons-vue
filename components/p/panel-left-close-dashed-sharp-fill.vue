<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hwv8c50wu"/><path class="dwlz50b1l"/><path class="zsuk8rbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-dashed-sharp-fill" /></template>
<style>
.dwlz50b1l {
  d: path("M17 3L21 3L21 7M21 17L21 21L17 21M12 3L15 3M12 21L15 21M21 9.5L21 14.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hwv8c50wu {
  fill: currentColor;
  d: path("M3 2L9 2C9.5523 2 10 2.4477 10 3L10 21C10 21.5523 9.5523 22 9 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.zsuk8rbci {
  d: path("M16.2929 8.7071L13 12L16.2929 15.2929");
}

</style>
