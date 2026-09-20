<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zqbjehbqe"/><path class="gcalxb98a"/><path class="xemj-cgvt"/><path class="ld2fqqd_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:salt-outline-bold" /></template>
<style>
.gcalxb98a {
  d: path("M8 13h8");
}

.ld2fqqd_p {
  d: path("M13 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xemj-cgvt {
  d: path("M9 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zqbjehbqe {
  d: path("M8 21V11l2 -2h4l2 2v10Z");
}

</style>
