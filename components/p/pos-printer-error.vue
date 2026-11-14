<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dryt_s0rg"/><path class="wc3kc43yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-printer-error" /></template>
<style>
.dryt_s0rg {
  d: path("M12.115 21.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 18v-5.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 9h12q.161 0 .322.015t.319.044t.314.074t.306.102t.295.13q.145.072.282.157q.138.084.267.181t.248.206t.228.228t.207.247t.183.266t.158.281q.072.144.131.295q.059.15.103.305q.045.155.075.314q.03.158.046.319M6.5 9V2.5h11V9m-8-3.5h5m-12 7H14M6 17h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc3kc43yj {
  d: path("M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-2.25v2.75m0 2h.01");
}

</style>
