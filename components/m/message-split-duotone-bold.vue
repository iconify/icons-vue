<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="znztjab3f"/><path class="ls8njpjqg"/><path class="kz4ewmbky"/><path class="phw9aqbbx"/><path class="hz28nvbkj"/><path class="n-059ea3n"/><path class="vxqaiwbbu"/><path class="gcu5j9bzw"/><path class="wo23ajbmh"/><path class="rm0jxkbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-split-duotone-bold" /></template>
<style>
.gcu5j9bzw {
  d: path("M14 4h3v3");
}

.hz28nvbkj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 20h3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kz4ewmbky {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ls8njpjqg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-059ea3n {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.phw9aqbbx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rm0jxkbqz {
  d: path("M14 20h3v-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vxqaiwbbu {
  d: path("m9 12 8 -8");
}

.wo23ajbmh {
  d: path("m9 12 8 8");
}

.znztjab3f {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
