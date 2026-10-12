<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_vrkxb-f"/><path class="wtgd_8brf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quotation-sharp" /></template>
<style>
.wtgd_8brf {
  d: path("M13.75 2.75v5.5h5.5m-11 .5h2.5m-2.5 3.5h4m3 2.25H18l.53.53l1.94 1.94l.53.53l-.53.53l-2.44 2.44l-.53.53l-.53-.53l-1.94-1.94l-.53-.53v-3.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_vrkxb-f {
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

</style>
