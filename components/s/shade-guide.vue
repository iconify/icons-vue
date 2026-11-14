<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ioklxpbls"/><path class="d8sa-cgwr"/><path class="irlq7f6jj"/><path class="i16w7puce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shade-guide" /></template>
<style>
.d8sa-cgwr {
  d: path("M8.963 5.346za1.5 1.5 0 0 1 1.799 1.124l1.462 6.334a1.5 1.5 0 0 1-1.124 1.799a1.5 1.5 0 0 1-1.799-1.125L7.839 7.145a1.5 1.5 0 0 1 1.124-1.799");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i16w7puce {
  d: path("M20.311 7.862za1.5 1.5 0 0 1 .259 2.105l-4.002 5.122a1.5 1.5 0 0 1-2.105.259a1.5 1.5 0 0 1-.259-2.106l4.002-5.122a1.5 1.5 0 0 1 2.105-.258M10.5 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.ioklxpbls {
  d: path("M3.689 7.862za1.5 1.5 0 0 1 2.105.258l4.002 5.122a1.5 1.5 0 0 1-.259 2.106a1.5 1.5 0 0 1-2.105-.259L3.43 9.967a1.5 1.5 0 0 1 .259-2.105");
}

.irlq7f6jj {
  d: path("M15.037 5.346za1.5 1.5 0 0 1 1.124 1.799l-1.462 6.333a1.5 1.5 0 0 1-1.799 1.125a1.5 1.5 0 0 1-1.124-1.799l1.462-6.334a1.5 1.5 0 0 1 1.799-1.124");
}

</style>
