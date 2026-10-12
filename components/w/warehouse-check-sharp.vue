<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tndr_nb1o"/><path class="k75yc8nwx"/><path class="j272i8j_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warehouse-check-sharp" /></template>
<style>
.j272i8j_u {
  d: path("M8 15h8v6.25H8zm4 0v6.25M8 18h8");
}

.k75yc8nwx {
  d: path("M5.75 21.25v-9.5h12.5v9.5");
}

.tndr_nb1o {
  d: path("M2.75 20V8.5l1.09-.62l7.07-4.01L12 3.25l1.09.62l7.07 4.01l1.09.62v12.75H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
