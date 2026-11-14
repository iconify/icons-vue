<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yvn-s5tpu"/><path class="gcuatvb3p"/><path class="nkdh0nb9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:peer-review" /></template>
<style>
.gcuatvb3p {
  d: path("m14.5 9.5l1.5.25l-.25-1.5m.147 6a4.5 4.5 0 0 1-7.794 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkdh0nb9e {
  d: path("M9.5 14.5L8 14.25l.25 1.5");
}

.yvn-s5tpu {
  d: path("M2.25 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2 18c0-2.5 1-4 2.25-4s2.25 1.5 2.25 4Zm15.75-8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M17.5 18c0-2.5 1-4 2.25-4S22 15.5 22 18Zm-5.206-7.53za1.25 1.25 0 0 0 1.07.778a.317.317 0 0 1 .181.559a1.25 1.25 0 0 0-.408 1.258a.317.317 0 0 1-.476.345a1.25 1.25 0 0 0-1.322 0a.317.317 0 0 1-.476-.345a1.25 1.25 0 0 0-.408-1.258a.317.317 0 0 1 .181-.559a1.25 1.25 0 0 0 1.07-.778a.317.317 0 0 1 .588 0m-4.191-.72a4.5 4.5 0 0 1 7.794 0");
}

</style>
