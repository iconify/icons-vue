<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zqbjehbqe"/><path class="gcalxb98a"/><path class="xemj-cgvt"/><path class="ld2fqqd_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:salt-outline-thin" /></template>
<style>
.gcalxb98a {
  d: path("M8 13h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld2fqqd_p {
  d: path("M13 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xemj-cgvt {
  d: path("M9 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zqbjehbqe {
  d: path("M8 21V11l2 -2h4l2 2v10Z");
}

</style>
