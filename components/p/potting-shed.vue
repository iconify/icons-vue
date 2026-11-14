<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9h11518n"/><path class="v4u7r_b-f"/><path class="t4wepcbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potting-shed" /></template>
<style>
.t4wepcbkl {
  d: path("M9 13h6v8H9Zm0 0l6 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4u7r_b-f {
  d: path("M4.5 9v12h15V9");
}

.x9h11518n {
  d: path("m2.5 10.5l9.5-7l9.5 7");
}

</style>
