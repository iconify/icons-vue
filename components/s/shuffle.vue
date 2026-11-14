<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d4f3eobuu"/><path class="fkykw0-ih"/><path class="tqih8-7un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shuffle" /></template>
<style>
.d4f3eobuu {
  d: path("M4 7.5h2.5c4 0 7 9 11 9H20");
}

.fkykw0-ih {
  d: path("m17 13.5l3 3l-3 3m-13-3h2.5c4 0 7-9 11-9H20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tqih8-7un {
  d: path("m17 4.5l3 3l-3 3");
}

</style>
