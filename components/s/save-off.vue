<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm5zddcps"/><path class="nwco7ibdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:save-off" /></template>
<style>
.cm5zddcps {
  d: path("M7.9 4h7.15q.345 0 .683.067t.656.199t.606.324q.286.191.53.435l1.45 1.45q.244.244.435.53q.192.287.324.606q.132.318.199.656T20 8.95v7.142M16.066 20H7.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T4 16.5V7.923");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwco7ibdd {
  d: path("M11.986 8H14q.098 0 .195-.019t.188-.057t.173-.093t.151-.124t.124-.151t.093-.173t.057-.188T15 7V4M3.5 3.5l17 17");
}

</style>
