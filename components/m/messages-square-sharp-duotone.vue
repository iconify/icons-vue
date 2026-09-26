<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vv5gchm0k"/><path class="jg_dgbbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jg_dgbbmg {
  stroke-opacity: 0.4;
  d: path("M6.2929 12.7071L3 16L3 3L17 3");
}

.vv5gchm0k {
  fill: currentColor;
  d: path("M12 9L21 9C21.5523 9 22 9.4477 22 10L22 21C22 21.5523 21.5523 22 21 22C20.7348 22 20.4804 21.8946 20.2929 21.7071L17.5858 19L12 19C11.4477 19 11 18.5523 11 18L11 10C11 9.4477 11.4477 9 12 9Z");
  stroke: none;
}

</style>
