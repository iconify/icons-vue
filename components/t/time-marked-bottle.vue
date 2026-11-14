<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azz_stbpj"/><path class="zae5yzbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-marked-bottle" /></template>
<style>
.azz_stbpj {
  d: path("M9 7.5v1q-2 1-2 3.5v8q0 1.5 1.5 1.5h7q1.5 0 1.5-1.5v-8q0-2.5-2-3.5v-1m-6.5-3h7v3h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zae5yzbjd {
  d: path("M12 6.5a2 2 0 0 1 0-4M10 12h3m-3 3h2m-2 3h3");
}

</style>
