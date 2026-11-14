<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="v26iolbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-electrician" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.v26iolbtb {
  d: path("m11.256 7.799l-2.547 3.358A.993.993 0 0 0 9.5 12.75h.217a1.5 1.5 0 0 1 1.477 1.757L11 15.625a.775.775 0 0 0 1.361.627l2.864-3.461a.941.941 0 0 0-.725-1.541h-.364a1.5 1.5 0 0 1-1.494-1.63l.108-1.245a.833.833 0 0 0-1.494-.576");
}

</style>
