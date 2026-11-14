<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u_s649tgm"/><path class="t4dz5ojor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:next-episode" /></template>
<style>
.t4dz5ojor {
  d: path("m8.5 7l5 3.25l-5 3.25ZM16 7v6.5");
}

.u_s649tgm {
  d: path("M2.5 3.5h19V17h-19Zm5.5 17h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
