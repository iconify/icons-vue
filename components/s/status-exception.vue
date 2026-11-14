<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-0tt363w"/><path class="fa6-kr0qj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:status-exception" /></template>
<style>
.fa6-kr0qj {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10m6-7V18m0 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-0tt363w {
  d: path("m15.645 19.571l-2.943 1.557q-.162.086-.34.13t-.362.044t-.362-.044t-.34-.13l-7-3.705q-.09-.048-.173-.107t-.156-.129t-.138-.15t-.116-.166t-.093-.181t-.067-.191q-.028-.099-.041-.199q-.014-.101-.014-.203V7.903q0-.102.014-.203q.013-.1.041-.199q.027-.098.067-.191q.04-.094.093-.181q.052-.087.116-.166t.138-.15t.156-.129t.173-.107l7-3.705q.162-.086.34-.13T12 2.698t.362.044t.34.13l7 3.705q.09.048.173.107t.156.129q.074.07.138.15t.116.166q.053.087.093.181q.04.093.067.191q.028.099.041.199q.014.101.014.203v5.432");
}

</style>
