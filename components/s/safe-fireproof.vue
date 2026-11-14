<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlhh44bqx"/><path class="y1b9q2b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safe-fireproof" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlhh44bqx {
  d: path("M11.915 19.5H6.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 16V7q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 3.5h11q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21 7v5.042M6.5 19.5V21");
}

.y1b9q2b8c {
  d: path("M7 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M17 8v3.5m1 10c-2.25 0-3.5-1.5-3.25-3.25c.25-1.5 1.25-2 1.5-3.25c.75.75 1 1.5 1 2.25c.75-.75 1.5-2 1.5-3.5c1.75 1.5 2.75 3.25 2.75 4.75c0 1.75-1.5 3-3.5 3");
}

</style>
