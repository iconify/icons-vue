<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a0_sqbbam"/><path class="gybvl8b6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-training-mode" /></template>
<style>
.a0_sqbbam {
  d: path("M14.2 12.5H2.5v-10H17v8.9m-8.25 1.1V19M4.5 19H13v2.5H4.5Zm1-13h5m-5 3.25H8m3 0h3m.75 6L18 14l3.25 1.25q.5.25 0 .5L18 17l-3.25-1.25q-.5-.25 0-.5Z");
}

.gybvl8b6f {
  d: path("M16 16.5V19c1.25 1.25 2.75 1.25 4 0v-2.5m1-.75v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
