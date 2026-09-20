<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stacked-bar-outline-thin" /></template>
<style>
.axyqg5uel {
  d: path("M16 14v6");
}

.bgz3owcvd {
  d: path("M8 4v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nj9g-accq {
  d: path("M16 8v3");
}

.vux4gkbhn {
  d: path("M8 14v6");
}

</style>
