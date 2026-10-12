<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sk12xdbfj"/><circle class="qpdl54bmi"/><path class="kw5260m_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:windmill-farm-sharp" /></template>
<style>
.kw5260m_p {
  d: path("M11 3v9M6.5 7.5h9M7.8 4.3l6.4 6.4m0-6.4l-6.4 6.4m10.52-5.65l2.36-.85l.57-.2v7l-.57-.2l-2.36-.85l-.57-.2v-4.5z");
}

.qpdl54bmi {
  cx: 11px;
  cy: 7.5px;
  r: 4.5px;
}

.sk12xdbfj {
  d: path("M7.5 21.25L11 12l3.5 9.25m-5.9-3h4.8M15.5 7.5h2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
