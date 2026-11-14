<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gomq5vots"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouse-off" /></template>
<style>
.gomq5vots {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.805 3.773q.232-.186.492-.331q.259-.144.54-.243q.28-.099.573-.149T10 3h4q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v7.042m-1.235 6.626q-.235.2-.502.355q-.267.156-.556.262t-.594.161Q14.309 21 14 21h-4q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177t-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T6.5 17.5v-7.027M12 6.5v1.6M3.5 3.5l17 17");
}

</style>
