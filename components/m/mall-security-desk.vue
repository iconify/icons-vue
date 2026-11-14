<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkkpombgi"/><path class="bq78nbbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mall-security-desk" /></template>
<style>
.bkkpombgi {
  d: path("M3 9c0-3.5 4-6 9-6s9 2.5 9 6l-2 3H5Zm3.5 3h11a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 14v-.5A1.5 1.5 0 0 1 6.5 12M5 15.5c0 3 3 5 7 5s7-2 7-5");
}

.bq78nbbsr {
  d: path("m12.367 5.869l.016.036a1.5 1.5 0 0 0 1.253.911l.039.003a.399.399 0 0 1 .227.699l-.03.026a1.5 1.5 0 0 0-.478 1.473l.009.039a.399.399 0 0 1-.595.431l-.033-.02a1.5 1.5 0 0 0-1.55 0l-.033.02a.399.399 0 0 1-.595-.431l.009-.039a1.5 1.5 0 0 0-.478-1.473l-.03-.026a.399.399 0 0 1 .227-.699l.039-.003a1.5 1.5 0 0 0 1.253-.911l.016-.036a.399.399 0 0 1 .734 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
