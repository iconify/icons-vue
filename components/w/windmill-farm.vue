<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk12xdbfj"/><circle class="qpdl54bmi"/><path class="lcea_kgnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:windmill-farm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcea_kgnz {
  d: path("M11 3v9M6.5 7.5h9M7.8 4.3l6.4 6.4m0-6.4l-6.4 6.4m10.52-5.65l2.36-.85q.57-.2.57.4v5.8q0 .6-.57.4l-2.36-.85q-.57-.2-.57-.8v-3.3q0-.6.57-.8");
}

.qpdl54bmi {
  cx: 11px;
  cy: 7.5px;
  r: 4.5px;
}

.sk12xdbfj {
  d: path("M7.5 21.25L11 12l3.5 9.25m-5.9-3h4.8M15.5 7.5h2.25");
}

</style>
