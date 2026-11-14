<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2s-5jbws"/><path class="ek612ob6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-gift-receipt" /></template>
<style>
.ek612ob6p {
  d: path("M18 17.5c-1.5-2.25-3.75-2.25-3.75-.75s2.25 2 3.75.75m0 0c1.5-2.25 3.75-2.25 3.75-.75s-2.25 2-3.75.75m-.75 1.75l-.5 2.25m2-2.25l.5 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2s-5jbws {
  d: path("M13.915 21.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 18v-3.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 11h10q.254 0 .505.037q.251.036.495.109q.243.072.473.179q.231.107.443.246q.213.139.403.307q.19.169.354.362q.164.194.298.41t.236.448M6 11V2.5h10V11M8.5 5.5h5m-5 2.75h3m-9 6.25h9.6");
}

</style>
