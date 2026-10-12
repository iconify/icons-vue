<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lda54ab4v"/><circle class="w1y-8_bhe"/><path class="g_vya492f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:unsubscribe-sharp" /></template>
<style>
.g_vya492f {
  d: path("M16 6.25h3");
}

.lda54ab4v {
  d: path("M11 4.25a6 6 0 0 0-6 6v3.944l-.7.856l-.6.75l-1.56 1.95h17.72L18.3 15.8l-.6-.75l-.7-.856V11.5m-8.25 8.75l.825.75h2.85l.825-.75");
}

.w1y-8_bhe {
  cx: 17.5px;
  cy: 6.25px;
  r: 3.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
