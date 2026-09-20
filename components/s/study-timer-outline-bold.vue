<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqda50bqs"/><path class="wsg9rhonx"/><path class="jms1xqp8l"/><path class="zkgvk4bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:study-timer-outline-bold" /></template>
<style>
.jms1xqp8l {
  d: path("M9 3h6");
}

.nqda50bqs {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wsg9rhonx {
  d: path("M12 8v5h4");
}

.zkgvk4bog {
  d: path("M12 2v3");
}

</style>
