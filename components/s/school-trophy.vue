<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="atvtat2wa"/><path class="w60vli0um"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:school-trophy" /></template>
<style>
.atvtat2wa {
  d: path("M7 3.5h10v6a5 5 0 0 1-10 0Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5V20m-4 0h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w60vli0um {
  d: path("m12.367 6.369l.016.036a1.5 1.5 0 0 0 1.253.911l.039.003a.399.399 0 0 1 .227.699l-.03.026a1.5 1.5 0 0 0-.478 1.473l.009.039a.399.399 0 0 1-.595.431l-.033-.02a1.5 1.5 0 0 0-1.55 0l-.033.02a.399.399 0 0 1-.595-.431l.009-.039a1.5 1.5 0 0 0-.478-1.473l-.03-.026a.399.399 0 0 1 .227-.699l.039-.003a1.5 1.5 0 0 0 1.253-.911l.016-.036a.399.399 0 0 1 .734 0");
}

</style>
