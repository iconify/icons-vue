<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s063vqbfs"/><path class="di8bmkbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raincoat" /></template>
<style>
.di8bmkbwn {
  d: path("M10.5 8q0-2.25 1.5-2.25c1.5 0 1.5.75 1.5 2.25M12 10v11.25M6.25 12.5v8.75m11.5-8.75v8.75M4 2.75c-.6.9-1.25 1.6-1.25 2.4a1.25 1.25 0 0 0 2.5 0c0-.8-.65-1.5-1.25-2.4m16 0c-.6.9-1.25 1.6-1.25 2.4a1.25 1.25 0 0 0 2.5 0c0-.8-.65-1.5-1.25-2.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s063vqbfs {
  d: path("m8.27 5.87l.46-.99q.52-1.13 1.69-1.56l.41-.14q1.17-.43 2.34 0l.41.14q1.17.43 1.69 1.56l.46.99Q16.25 7 17.4 7.49l1.2.52q1.15.49 1.31 1.73l1.18 9.27q.16 1.24-1.04 1.58l-1.1.32q-1.2.34-2.45.34h-9q-1.25 0-2.45-.34l-1.1-.32q-1.2-.34-1.04-1.58l1.18-9.27Q4.25 8.5 5.4 8.01l1.2-.52Q7.75 7 8.27 5.87");
}

</style>
