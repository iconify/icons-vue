<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n5tft7wyn"/><path class="oh5f0ih0f"/><path class="kfr5ppb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:privacy-policy-sharp" /></template>
<style>
.kfr5ppb5y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17h.01");
}

.n5tft7wyn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h13v18.5h-13zM7 7h6.5M7 10h6.5M7 13h3");
}

.oh5f0ih0f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 17c1.2-1.6 2.7-2.5 4.25-2.5s3.05.9 4.25 2.5c-1.2 1.6-2.7 2.5-4.25 2.5s-3.05-.9-4.25-2.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
