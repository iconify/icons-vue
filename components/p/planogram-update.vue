<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygwdhfbsk"/><path class="wsi6--9rt"/><path class="k9f0qzqhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:planogram-update" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9f0qzqhp {
  d: path("m15.75 12.5l2 2l-2 2");
}

.wsi6--9rt {
  d: path("M6.5 5.5h2A1.5 1.5 0 0 1 10 7v1a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 5 8V7a1.5 1.5 0 0 1 1.5-1.5m8 0h2A1.5 1.5 0 0 1 18 7v1a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 13 8V7a1.5 1.5 0 0 1 1.5-1.5m-8 5.75h2a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m6.509 2.667Q13 13.834 13 13.75v-1.036M6.5 17h2a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 8.5 21h-2A1.5 1.5 0 0 1 5 19.5v-1A1.5 1.5 0 0 1 6.5 17m14.281-.75a3.5 3.5 0 1 1-3.031-1.75");
}

.ygwdhfbsk {
  d: path("M12.215 21H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 17.5v-11q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v7.042M2.5 9.5h19m-19 5.75h9.6");
}

</style>
