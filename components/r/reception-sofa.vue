<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qyv03sbyd"/><path class="b2s4mobgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reception-sofa" /></template>
<style>
.b2s4mobgo {
  d: path("M2.5 20v-5.5a1.25 1.25 0 0 1 2.5 0v2h8v-2a1.25 1.25 0 0 1 2.5 0V20ZM19.75 8v13.5m0-13.5za1.404 1.404 0 0 0 1.37-1.708l-.457-2.06a.935.935 0 0 0-.913-.732a.935.935 0 0 0-.913.732l-.457 2.06A1.404 1.404 0 0 0 19.75 8M18 21.5h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyv03sbyd {
  d: path("M4 13.5v-2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v2");
}

</style>
