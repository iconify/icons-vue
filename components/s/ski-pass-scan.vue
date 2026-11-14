<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_upjsp4x"/><path class="elikedbhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-pass-scan" /></template>
<style>
.elikedbhn {
  d: path("M8 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M6.5 15.5l3-4l3 4m5.5.5a3.25 3.25 0 0 1 0 4m2.25-5.75a6 6 0 0 1 0 7.5");
}

.g_upjsp4x {
  d: path("M15.382 16.902q-.037.139-.085.274t-.108.266q-.059.13-.128.256q-.07.125-.149.244q-.08.12-.169.232t-.187.217t-.204.201t-.22.184q-.114.087-.234.165q-.121.077-.247.145t-.258.125t-.267.103t-.275.081t-.28.058q-.142.024-.285.035T12 19.5H7q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3.5 16V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T7 2.5h5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T15.5 6v8.842");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
