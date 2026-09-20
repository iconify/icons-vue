<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jfvoq9bhn"/><path class="slz7u0oyn"/><path class="h7bcztycq"/><path class="pkaragbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:migration-down-outline-bold" /></template>
<style>
.h7bcztycq {
  d: path("M12 8v8");
}

.jfvoq9bhn {
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h15A2.5 2.5 0 0 1 22 4.5 2.5 2.5 0 0 1 19.5 7h-15A2.5 2.5 0 0 1 2 4.5");
}

.pkaragbav {
  d: path("m8 12 4 4 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.slz7u0oyn {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
}

</style>
