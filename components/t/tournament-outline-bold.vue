<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="due_v2swe"/><path class="w5i79a2na"/><path class="l1jjkky7x"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tournament-outline-bold" /></template>
<style>
.due_v2swe {
  d: path("M8 4h8v5c0 3 -1.5 5 -4 5s-4 -2 -4 -5Z");
}

.l1jjkky7x {
  d: path("M8 18h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w5i79a2na {
  d: path("M12 14v4");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
