<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t4du7bbsp"/><path class="ddb1dwb-p"/><path class="hswv-t1fg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-card-sharp" /></template>
<style>
.ddb1dwb-p {
  d: path("m8.9 8.88l1.73.99l.65.38v3.5l-.65.38l-1.73.99l-.65.38l-.65-.38l-1.73-.99l-.65-.38v-3.5l.65-.38l1.73-.99l.65-.38z");
}

.hswv-t1fg {
  d: path("M5.22 10.25L8.25 12l3.03-1.75M8.25 12v3.5");
}

.t4du7bbsp {
  d: path("M2.75 4.75h18.5v14.5H2.75zM13.25 10h4.5m-4.5 4h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
