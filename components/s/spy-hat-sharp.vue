<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xqimttxnp"/><path class="igtrnac2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spy-hat-sharp" /></template>
<style>
.igtrnac2o {
  d: path("M8.5 15.75L12 20l3.5-4.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xqimttxnp {
  d: path("m6.5 11.72l1.35-5.97l.4-1.592L9.8 4.7l2.2.8l2.2-.8l1.55-.542l.4 1.592l1.35 5.97q-5.5 1.06-11 0Zm-3.75-.97q1.88.61 3.75.97m11 0q1.88-.36 3.75-.97M2.96 20.02l.08-.54l.21-1.23l1.09-.61l2.32-1.28l1.09-.61h8.5l1.09.61l2.32 1.28l1.09.61l.21 1.23l.08.54l.21 1.23H2.75z");
}

</style>
