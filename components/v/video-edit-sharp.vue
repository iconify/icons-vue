<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b6ouz4rhm"/><path class="la9inmbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-edit-sharp" /></template>
<style>
.b6ouz4rhm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8h18.5v8H2.75z");
}

.la9inmbxz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 10h.01M12 10h.01m7.24 0h.01M4.75 14h.01M12 14h.01m7.24 0h.01M8 5.25v13.5m8-13.5v13.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
