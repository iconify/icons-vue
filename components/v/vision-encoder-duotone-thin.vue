<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pk8nmlbpc"/><path class="wf1juibku"/><path class="ne8s-4gza"/><path class="wsk1_9dbv"/><path class="urighfbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vision-encoder-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ne8s-4gza {
  d: path("M2 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.pk8nmlbpc {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.urighfbup {
  d: path("m18.5 9 3 3 -3 3 -3 -3Z");
}

.wf1juibku {
  fill: currentColor;
  d: path("m18.5 9 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wsk1_9dbv {
  d: path("m5 15 2 -2 2 2");
}

</style>
