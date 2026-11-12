<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rzhz1qpjc"/><path class="vjskc3bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shadow-line-duotone" /></template>
<style>
.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzhz1qpjc {
  d: path("M17.0002 20.66C12.2173 23.4214 6.10139 21.7826 3.33999 16.9997C0.578493 12.2168 2.21729 6.10087 7.00019 3.33947C8.94979 2.21387 11.1209 1.81937 13.196 2.07087C16.2117 2.43637 19.0246 4.16637 20.6605 6.99967C22.2963 9.83297 22.388 13.1341 21.1967 15.9286C20.377 17.8514 18.9498 19.5344 17.0002 20.66Z");
}

.vjskc3bnx {
  stroke-linecap: round;
  d: path("M16 16L19.0727 19.0727M18 13L21.1151 16.1151M13 18L16.1148 21.1148M19 9L22.0019 12.0019M9 19L12.0014 22.0014");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
