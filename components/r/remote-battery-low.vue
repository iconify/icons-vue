<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o1m_dnklu"/><path class="ik54e-bky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:remote-battery-low" /></template>
<style>
.ik54e-bky {
  d: path("M7.25 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14 15.75h4.5a1 1 0 0 1 1 1V17h1v2h-1v.25a1 1 0 0 1-1 1H14a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1Zm1 1.5v1.5");
}

.o1m_dnklu {
  d: path("M10.7 21.5H4.5v-19h9V13M9 5.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
