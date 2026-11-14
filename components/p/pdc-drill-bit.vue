<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jl8jcjbbf"/><path class="s1u2uqo-d"/><path class="h59y9_xcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pdc-drill-bit" /></template>
<style>
.h59y9_xcz {
  fill: currentColor;
  d: path("M12 5h.01M12 7.5h.01m6.052 8h.01m-2.175-1.25h.01M5.938 15.5h.01m2.155-1.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl8jcjbbf {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0");
}

.s1u2uqo-d {
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 2.75zA2.25 2.25 0 0 1 14.25 5v2.25A2.25 2.25 0 0 1 12 9.5a2.25 2.25 0 0 1-2.25-2.25V5A2.25 2.25 0 0 1 12 2.75m8.011 13.875za2.25 2.25 0 0 1-3.074.824l-1.948-1.125a2.25 2.25 0 0 1-.824-3.074a2.25 2.25 0 0 1 3.074-.824l1.948 1.125a2.25 2.25 0 0 1 .824 3.074m-16.022 0za2.25 2.25 0 0 1 .824-3.074l1.948-1.125a2.25 2.25 0 0 1 3.074.824a2.25 2.25 0 0 1-.824 3.074l-1.948 1.125a2.25 2.25 0 0 1-3.074-.824");
}

</style>
