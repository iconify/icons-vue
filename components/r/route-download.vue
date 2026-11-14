<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc159-blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-download" /></template>
<style>
.vc159-blj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 18.5h3.1m3.572-5.995Q15.086 12.5 15 12.5H9q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T5.5 9t.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084q.169-.033.34-.05T9 5.5h6.5m-12 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 9V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
