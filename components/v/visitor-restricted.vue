<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhmo12msi"/><path class="wo3c02m2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visitor-restricted" /></template>
<style>
.hhmo12msi {
  d: path("M10.9 7H14q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311t.115.323t.084.333q.033.169.05.34t.017.343v3.042m-.997 6.905q-.245.25-.534.447q-.289.196-.611.332q-.323.136-.666.205q-.342.069-.692.069h-4q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177t-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T6.5 18v-7.525m4.399-3.528Q11.432 7 12 7c3.5 0 6-1.5 8-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wo3c02m2z {
  d: path("M9.831 13.728L12 18.5l.81-1.783M3.5 3.5l17 17");
}

</style>
