<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0lee0ovb"/><path class="ckxiefb_m"/><path class="e8wg7vb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trophy-sharp-duotone" /></template>
<style>
.ckxiefb_m {
  fill: currentColor;
  d: path("M18 1C18.5523 1 19 1.44772 19 2V9C19 12.866 15.866 16 12 16C8.13402 16 5 12.866 5 9V2C5 1.44772 5.44772 1 6 1H18Z");
  stroke: none;
}

.e8wg7vb-j {
  d: path("M6 19H18V22H6V19Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0lee0ovb {
  stroke-opacity: 0.4;
  d: path("M6 5H2V11H6.3249M18 5H22V11H17.6751M12 15V19");
}

</style>
