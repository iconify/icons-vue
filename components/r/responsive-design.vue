<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qomuwgbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:responsive-design" /></template>
<style>
.qomuwgbdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.715 15H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 11.5V7q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3.5h8q.149 0 .298.013q.148.012.295.038t.292.063t.285.087t.276.112t.266.134q.13.073.254.157q.123.084.239.178t.223.197q.107.104.206.216t.186.232q.089.121.166.248t.145.26q.067.134.122.273q.055.138.098.281t.074.289M10 15v4m-2.75 0h5.5m5.375-10h.75a2.625 2.625 0 0 1 2.625 2.625v6.75A2.625 2.625 0 0 1 18.875 21h-.75a2.625 2.625 0 0 1-2.625-2.625v-6.75A2.625 2.625 0 0 1 18.125 9");
}

</style>
