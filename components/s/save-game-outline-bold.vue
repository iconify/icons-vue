<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eq8p65fcb"/><path class="itwbxpr-a"/><path class="kct9dt-jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:save-game-outline-bold" /></template>
<style>
.eq8p65fcb {
  d: path("M4 4v16h16V4Z");
}

.itwbxpr-a {
  d: path("M8 4v5h8V4");
}

.kct9dt-jd {
  d: path("M8 20v-6h8v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
