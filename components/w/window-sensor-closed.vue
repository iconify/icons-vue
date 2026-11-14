<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_6bvbcyi"/><path class="nhmmpl-_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-sensor-closed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_6bvbcyi {
  d: path("M12.415 19.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 2.5h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T19.5 6v7.442M9 2.5v17");
}

.nhmmpl-_g {
  d: path("M14.25 5.5h.5a1.75 1.75 0 0 1 1.75 1.75V8a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 12.5 8v-.75a1.75 1.75 0 0 1 1.75-1.75m0 4.25h.5a1.75 1.75 0 0 1 1.75 1.75v.75A1.75 1.75 0 0 1 14.75 14h-.5a1.75 1.75 0 0 1-1.75-1.75v-.75a1.75 1.75 0 0 1 1.75-1.75m.5 8.25l2 2L21 15.75");
}

</style>
