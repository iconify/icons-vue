<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="atcmxjbma"/><path class="p4idz7btn"/><path class="h6srt4n9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-check-outline-thin" /></template>
<style>
.atcmxjbma {
  d: path("M4 5h12");
}

.h6srt4n9a {
  d: path("m14 15 3 3 5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4idz7btn {
  d: path("M10 5v10");
}

</style>
