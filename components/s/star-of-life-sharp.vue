<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="raor16j0s"/><path class="gjmy25xrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-of-life-sharp" /></template>
<style>
.gjmy25xrk {
  d: path("M12 6.5v11M9.75 15c0-1.75 4.5-1.25 4.5-3s-4.5-1.25-4.5-3");
}

.raor16j0s {
  d: path("M9.75 3.25H15V6.8l.65-.37l1.78-1.03l.65-.37l.38.65l2.24 3.89l.38.65l-.65.38l-1.78 1.02L18 12l.65.38l1.78 1.02l.65.38l-.38.65l-2.24 3.89l-.38.65l-.65-.37l-1.78-1.03l-.65-.37v3.55H9V17.2l-.65.37l-1.78 1.03l-.65.37l-.38-.65l-2.24-3.89l-.38-.65l.65-.38l1.78-1.02L6 12l-.65-.38l-1.78-1.02l-.65-.38l.38-.65l2.24-3.89l.38-.65l.65.37l1.78 1.03l.65.37V3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
