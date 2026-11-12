<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h-yburvtu"/><path class="x8w5itp5u"/><path class="zhaqmra8c"/><path class="q91v76bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-linear" /></template>
<style>
.h-yburvtu {
  stroke-linecap: round;
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.8284 3.46447C19.6569 2 17.7712 2 14 2H10C6.22876 2 4.34315 2 3.17157 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.17157 20.5355C4.34315 22 6.22876 22 10 22Z");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q91v76bet {
  stroke-linecap: round;
  d: path("M17 10.5C16.1716 10.5 15.5 9.82843 15.5 9C15.5 8.17157 16.1716 7.5 17 7.5C17.8284 7.5 18.5 8.17157 18.5 9C18.5 9.82843 17.8284 10.5 17 10.5Z");
}

.x8w5itp5u {
  stroke-linecap: round;
  d: path("M15 17L15.8944 16.5528C16.572 16.214 17 15.5215 17 14.7639V10.5");
}

.zhaqmra8c {
  d: path("M10 16V16C12.2091 16 14 14.2091 14 12V12C14 9.79086 12.2091 8 10 8V8C7.79086 8 6 9.79086 6 12V12C6 14.2091 7.79086 16 10 16Z");
}

</style>
