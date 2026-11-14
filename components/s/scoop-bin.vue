<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yvgeq0bae"/><path class="pb7u_ccsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scoop-bin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb7u_ccsx {
  d: path("M6 14a2.5 2 0 0 0 5 0m0 0l8.5-7m-13 11h1m3 .5h1");
}

.yvgeq0bae {
  d: path("M4.493 10h11.014a1.75 1.75 0 0 1 1.735 1.976l-1.043 8a1.75 1.75 0 0 1-1.736 1.524H5.537a1.75 1.75 0 0 1-1.736-1.524l-1.043-8A1.75 1.75 0 0 1 4.493 10M3.017 6.105l.682-2.5A1.5 1.5 0 0 1 5.146 2.5h4.057a1.5 1.5 0 0 1 1.475 1.768l-.454 2.5A1.5 1.5 0 0 1 8.748 8H4.464a1.5 1.5 0 0 1-1.447-1.895M3.25 14h13.5");
}

</style>
