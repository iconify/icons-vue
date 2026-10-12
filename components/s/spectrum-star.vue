<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yk-ha9b1r"/><rect class="ku1051bqv"/><path class="kh-d4_ann"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spectrum-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh-d4_ann {
  d: path("M6.5 14.75v6.5m2.75-6.5v6.5m5.25-6.5v6.5m3.5-6.5v6.5");
}

.ku1051bqv {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.75px;
  rx: 1.5px;
}

.yk-ha9b1r {
  d: path("m12.14 3.07l1.03 2.31q.14.32.49.35l2.51.27q.35.03.09.27l-1.88 1.68q-.26.24-.19.58l.53 2.47q.07.34-.23.17L12.3 9.91q-.3-.18-.6 0l-2.19 1.26q-.3.17-.23-.17l.53-2.47q.07-.34-.19-.58L7.74 6.27q-.26-.24.09-.27l2.51-.27q.35-.03.49-.35l1.03-2.31q.14-.32.28 0");
}

</style>
