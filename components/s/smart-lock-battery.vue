<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0w-leqgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-lock-battery" /></template>
<style>
.i0w-leqgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.718 19.705q-.122.151-.261.288t-.292.257t-.318.223q-.166.103-.341.187q-.176.083-.36.147t-.374.107t-.384.064T9 21H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 17.5v-4q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 10h3q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v.642M4.75 10V6.75a2.75 2.75 0 0 1 5.5 0V10M7.5 13.5v4m8-1.75h4.25a1 1 0 0 1 1 1v.5h1v1.5h-1v.5a1 1 0 0 1-1 1H15.5a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1");
}

</style>
