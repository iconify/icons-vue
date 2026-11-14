<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vjg2z7bvn"/><path class="ib9kt0bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:public-holiday" /></template>
<style>
.ib9kt0bij {
  d: path("m3.75 6.75l4 2l-3.25 5Zm6 2.5h4.5l-2.25 6Zm6.5-.5l4-2l-.75 7ZM7.5 18.5h.01M12 20.25h.01m4.49-1.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjg2z7bvn {
  d: path("M2.5 5.5C8 10 16 10 21.5 5.5");
}

</style>
