<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="v74zc_fve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:profile-edit-outline-bold" /></template>
<style>
.f69zonn4h {
  d: path("M4 17a4 4 0 0 1 8 0");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v74zc_fve {
  d: path("m13 18 5 -5 2 2 -5 5Z");
}

</style>
