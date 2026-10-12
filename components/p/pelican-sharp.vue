<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wwjg2mxgy"/><path class="w8tf2lbwv"/><path class="s4qqaehyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pelican-sharp" /></template>
<style>
.s4qqaehyi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 13.5l2.357 2.75H14.5m-4 3v2m3-2v2M9.75 5h12.675L20.5 6.05l-5.75 3.2l-2.669 1.335L9.75 9Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w8tf2lbwv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5.5h.01");
}

.wwjg2mxgy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3h-2.5v10c0 3.75 2.5 6.25 6 6.25h3.5c3 0 5-1.5 6.5-4.25c-2.75-.5-5-1.75-7-3.75L12 9.5H9.75V3z");
}

</style>
