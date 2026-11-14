<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vesmmvbwc"/><path class="w-sr--wyc"/><path class="ko3v1dzsx"/><path class="svecogjhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sick-leave" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko3v1dzsx {
  d: path("M16.75 18v-2.75c0-.85.65-1.5 1.5-1.5s1.5.65 1.5 1.5V18c.75.5 1.25 1.25 1.25 2c0 1.1-1.25 2-2.75 2s-2.75-.9-2.75-2c0-.75.5-1.5 1.25-2");
}

.svecogjhw {
  fill: currentColor;
  d: path("M17.25 20a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.vesmmvbwc {
  d: path("M12.715 20.5H7q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3.5 17V8.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323t.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q6.828 5 7 5h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v2.842M8 3v4m8-4v4M3.5 10h17");
}

.w-sr--wyc {
  fill: currentColor;
  d: path("M8 12.25h1A1.75 1.75 0 0 1 10.75 14v.5A1.75 1.75 0 0 1 9 16.25H8a1.75 1.75 0 0 1-1.75-1.75V14A1.75 1.75 0 0 1 8 12.25");
}

</style>
