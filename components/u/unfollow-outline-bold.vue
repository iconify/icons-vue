<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ejfmpibyt"/><path class="fgh6wnb3a"/><path class="p8a31xr4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unfollow-outline-bold" /></template>
<style>
.ejfmpibyt {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.fgh6wnb3a {
  d: path("M6 17a4 4 0 0 1 8 0");
}

.p8a31xr4o {
  d: path("M16 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
