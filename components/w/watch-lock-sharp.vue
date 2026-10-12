<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="byh9n2bqq"/><path class="dm2uewa9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watch-lock-sharp" /></template>
<style>
.byh9n2bqq {
  d: path("M5.75 6.25h12.5v11.5H5.75zm3 0l.5-3.5h5.5l.5 3.5m-6.5 11.5l.5 3.5h5.5l.5-3.5");
}

.dm2uewa9g {
  d: path("M12 9.25V12l1.75 1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
