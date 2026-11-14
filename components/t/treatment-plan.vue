<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="unt33ubva"/><path class="znh8hzbwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treatment-plan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unt33ubva {
  d: path("M12.015 20H6.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 16.5V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 2.5H13q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T16.5 6v6.842");
}

.znh8hzbwm {
  d: path("m5.25 5.5l1-.5v3m-1 2.25c0-.5.5-.75 1-.75s1 .25 1 .75c0 .75-2 1.25-2 2.25h2m-2 1.75c.25-.25.65-.5 1-.5c.55 0 1 .35 1 .75c0 .6-.45.75-1 .75c.6 0 1 .35 1 .75c0 .6-.5 1-1 1c-.4 0-.75-.2-1-.5m4-10h4.25M9.25 11h4.25m-4.25 4.5H12m3.348 2.323l2.475-2.475a2 2 0 0 1 2.829 0a2 2 0 0 1 0 2.829l-2.475 2.475a2 2 0 0 1-2.829 0a2 2 0 0 1 0-2.829m1.238-1.237l2.828 2.828");
}

</style>
