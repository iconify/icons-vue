<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gs2u-ebtp"/><path class="ldyahhf1z"/><path class="a6z1jcjqs"/><path class="b6cdzhbpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-insurance-outline-bold" /></template>
<style>
.a6z1jcjqs {
  d: path("M8 16a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.b6cdzhbpu {
  d: path("M10 14v-2.5h4V14");
}

.gs2u-ebtp {
  d: path("M4.5 8.5a7.5 7.5 0 0 1 15 0");
}

.ldyahhf1z {
  d: path("M4.5 8.5h15");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
