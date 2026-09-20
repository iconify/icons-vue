<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eh4_3ebbt"/><path class="w57l-wb8f"/><path class="v_i-xnbbq"/><path class="oa7ibkb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-queue-agent-outline-bold" /></template>
<style>
.eh4_3ebbt {
  d: path("M4 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.oa7ibkb8p {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v_i-xnbbq {
  d: path("M16 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w57l-wb8f {
  d: path("M10 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
