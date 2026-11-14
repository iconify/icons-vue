<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2skb6bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voicemail-play" /></template>
<style>
.d2skb6bxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm13.259 3.492q.12.008.241.008q.172 0 .343-.017t.34-.05q.168-.034.333-.084t.323-.115t.311-.147t.294-.177q.143-.095.276-.204q.133-.11.255-.231q.121-.122.231-.255q.109-.133.204-.276q.096-.142.177-.294t.147-.311t.115-.323t.084-.333q.033-.169.05-.34T19.5 7.5t-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294q-.095-.143-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T16 4t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333t-.05.34t-.017.343q0 .28.044.556q.045.276.132.541t.217.514q.128.248.295.472M6 11h6.7m2.8 3l6 3.25l-6 3.25Z");
}

</style>
