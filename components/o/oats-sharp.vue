<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="u8ah95bgo"/><path class="rz85jebgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oats-sharp" /></template>
<style>
.rz85jebgw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 7.75h.01M6 7.75h.01M18 13.25h.01M6 13.25h.01M18 18.75h.01M6 18.75h.01");
}

.u8ah95bgo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V2.75m0 1c3 0 5 .75 5.75 3m-5.75-3c-3 0-5 .75-5.75 3M12 9.25c3 0 5 .75 5.75 3m-5.75-3c-3 0-5 .75-5.75 3m5.75 2.5c3 0 5 .75 5.75 3m-5.75-3c-3 0-5 .75-5.75 3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
