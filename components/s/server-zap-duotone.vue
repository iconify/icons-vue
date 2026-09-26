<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l4scvchkx"/><path class="qxb6e3bet"/><path class="r0sazqbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-zap-duotone" /></template>
<style>
.l4scvchkx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1L17 1C18.6569 1 20 2.3431 20 4L20 8C20 9.6569 18.6569 11 17 11L5 11C3.3431 11 2 9.6569 2 8L2 4C2 2.3431 3.3431 1 5 1ZM5 13L13 13C13.5523 13 14 13.4477 14 14L14 22C14 22.5523 13.5523 23 13 23L5 23C3.3431 23 2 21.6569 2 20L2 16C2 14.3431 3.3431 13 5 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxb6e3bet {
  d: path("M20 16L17 19L21 19L18 22");
}

.r0sazqbgm {
  fill: currentColor;
  d: path("M8 6C8 6.5523 7.5523 7 7 7C6.4477 7 6 6.5523 6 6C6 5.4477 6.4477 5 7 5C7.5523 5 8 5.4477 8 6ZM12 6C12 6.5523 11.5523 7 11 7C10.4477 7 10 6.5523 10 6C10 5.4477 10.4477 5 11 5C11.5523 5 12 5.4477 12 6ZM8 18C8 18.5523 7.5523 19 7 19C6.4477 19 6 18.5523 6 18C6 17.4477 6.4477 17 7 17C7.5523 17 8 17.4477 8 18ZM12 18C12 18.5523 11.5523 19 11 19C10.4477 19 10 18.5523 10 18C10 17.4477 10.4477 17 11 17C11.5523 17 12 17.4477 12 18Z");
  stroke: none;
}

</style>
