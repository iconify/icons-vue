<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="atc8_8bqq"/><path class="z3n4yvbgr"/><path class="rkq8elboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ultrasound-machine" /></template>
<style>
.atc8_8bqq {
  d: path("M12.115 15.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 12V6.5q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v5.142M11 15.5v6m-4 0h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkq8elboy {
  d: path("M15.875 13.935za2 2 0 0 1 2.732.732l1.25 2.166a2 2 0 0 1-.732 2.732a2 2 0 0 1-2.732-.732l-1.25-2.166a2 2 0 0 1 .732-2.732M19 19.75c.5 1.25 1.75 1.75 2.75 1.25");
}

.z3n4yvbgr {
  fill: currentColor;
  d: path("M14.874 11.295L11 5l-4 6.5q.365.23.754.417q.39.187.798.328t.83.234q.421.093.851.137q.429.045.861.039t.86-.06t.847-.159q.42-.104.824-.255");
}

</style>
