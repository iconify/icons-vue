<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1dsfyq6q"/><path class="oob83cbzo"/><path class="vjt_vebdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-swift-message" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1dsfyq6q {
  d: path("M21.5 12.042V16q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294q-.095.143-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05T18 19.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16V9q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 5.5 6 5.5h5.5");
}

.oob83cbzo {
  d: path("m2.5 7l8.5 6l2.429-1.754M14.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m0 0h7.5");
}

.vjt_vebdt {
  d: path("M18 2.75c-1.75 1.75-1.75 5.75 0 7.5");
}

</style>
