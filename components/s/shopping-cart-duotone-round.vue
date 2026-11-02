<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h_w62ealu"/><path class="qkl5g7bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h_w62ealu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.571 7H18a3 3 0 0 1 1.494.39c1.377.774 1.947 2.448 1.455 3.926l-1 3c-.228.683-.581 1.327-1.093 1.839c-.493.493-1.146.845-1.856.845h-6a5.15 5.15 0 0 1-4.962-3.725l-1.429-5A1 1 0 0 1 5.571 7");
}

.qkl5g7bmc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4c.846 0 1.662.816 2 2l2 7c.507 1.776 2.14 3 4 3h6c.796 0 1.602-.806 2-2l1-3c.492-1.476-.524-3-2-3H6m2 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
