<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw916wbix"/><path class="ztnv-abvf"/><path class="aispypb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mrr" /></template>
<style>
.aispypb3t {
  d: path("m16.5 13.5l1.5 1.25L16.5 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw916wbix {
  d: path("M12.515 20.5H7q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3.5 17V8.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323t.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q6.828 5 7 5h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v5.042M8 3v4m8-4v4M3.5 10h17");
}

.ztnv-abvf {
  d: path("M12.25 12.75q-.375-.75-1.5-.75c-1 0-1.5.5-1.5 1.25c0 1.392 2.797 1.062 3.201 2.404m-.408 1.221c-.315.238-.77.375-1.293.375c-.75 0-1.5-.25-1.75-.75m1.75-5.75V12m0 5.25v1.25m10.5-.5A3.25 3.25 0 1 1 18 14.75");
}

</style>
