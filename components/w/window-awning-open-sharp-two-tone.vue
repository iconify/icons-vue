<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wsu8-4b_q"/><path class="xufqmwmpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-open-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wsu8-4b_q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 2C20.486 2 20.902 2.35 20.985 2.829L22.89 13.829C22.94 14.12 22.86 14.418 22.67 14.644C22.48 14.869 22.199 15 21.904 15H21V20H23V22H1V20H3V15H2.096C1.801 15 1.521 14.869 1.331 14.644C1.141 14.418 1.06 14.12 1.11 13.829L3.015 2.829L3.034 2.741C3.15 2.308 3.544 2 4 2H20Z");
  stroke: none;
}

.xufqmwmpr {
  d: path("M4 14H2.095L4 3H12M4 14H20M4 14V21M12 3H20L21.904 14H20M12 3V14M20 14V21M3.048 8.5H20.952M1 21H23");
}

</style>
