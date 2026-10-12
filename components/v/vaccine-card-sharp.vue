<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="hk49g4b5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vaccine-card-sharp" /></template>
<style>
.hk49g4b5g {
  d: path("M6.75 8.25H13v2.5H6.75zM13 9.5h3m-10.75 0h1.5m-1 4.5h12.5m-12.5 2.25h8");
}

.hmz588b6d {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
