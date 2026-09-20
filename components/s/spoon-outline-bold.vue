<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cenf9z9qb"/><path class="e7fjltb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spoon-outline-bold" /></template>
<style>
.cenf9z9qb {
  d: path("M8 5a4 4 0 0 1 8 0c0 5 -2 8 -4 8s-4 -3 -4 -8");
}

.e7fjltb5i {
  d: path("M12 13v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
