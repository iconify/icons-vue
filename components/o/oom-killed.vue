<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="arv_7cm3c"/><path class="hw89z3bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oom-killed" /></template>
<style>
.arv_7cm3c {
  d: path("M14.6 12.5H2.5v-10h19v10h-.1m-1.8 0h-3.2");
}

.hw89z3bjp {
  d: path("M5.5 5.5h5v4h-5Zm8 0h5v4h-5Zm-8 7v3m3-3v3m3-3v3m4 0l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
