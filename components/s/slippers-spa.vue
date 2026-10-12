<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnwgujwqb"/><path class="wxnshliij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slippers-spa" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnwgujwqb {
  d: path("M2.85 8.66a3.75 4-6 0 1 7.46-.78c.37 3.48-.42 5.57-.05 9.06a2.75 3-6 0 1-5.47.57c-.37-3.48-1.57-5.37-1.94-8.85m10.84-.78a3.75 4 6 0 1 7.46.78c-.37 3.48-1.57 5.37-1.94 8.85a2.75 3 6 0 1-5.47-.57c.37-3.49-.42-5.58-.05-9.06");
}

.wxnshliij {
  d: path("M3.06 10.15q3.39-3.12 7.36-.77l.08 2.25q-3.79-2.11-7.06.74Zm10.52-.77q3.97-2.35 7.36.77l-.38 2.22q-3.27-2.85-7.06-.74Z");
}

</style>
