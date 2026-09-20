<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="he7cpnbxn"/><path class="ky10s_bai"/><path class="ru0la3bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-wrap-outline-bold" /></template>
<style>
.he7cpnbxn {
  d: path("M3 12h14");
}

.ky10s_bai {
  d: path("M17 12v3h-7");
}

.ru0la3bku {
  d: path("M12.5 12.5 10 15l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
