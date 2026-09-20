<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b_jss3b2t"/><path class="vpkfcbbqx"/><path class="wbm-b2ujk"/><path class="y-8u9wb8b"/><path class="l-8pkdhvs"/><path class="xhwe0sbyf"/><path class="ze3hawb4v"/><path class="vdq8lyksd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-depth-duotone-bold" /></template>
<style>
.b_jss3b2t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.5 4H4v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l-8pkdhvs {
  d: path("M6.5 4H4v16h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vdq8lyksd {
  d: path("M18 12v6");
}

.vpkfcbbqx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wbm-b2ujk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhwe0sbyf {
  d: path("M10 9v9");
}

.y-8u9wb8b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ze3hawb4v {
  d: path("M14 6v12");
}

</style>
