<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9-dhevzy"/><path class="mj0b5zu0d"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:washing-machine-timer" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.i9-dhevzy {
  d: path("M12.3 20H3V2.5h15v9.4M3 7h15");
}

.mj0b5zu0d {
  d: path("M13.716 13.737q.034-.242.034-.487q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05t-.343-.017t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34t-.017.343t.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147t.323.115t.333.084q.169.033.34.05t.343.017q.272 0 .54-.042q.269-.042.528-.125q.258-.083.501-.205t.464-.279M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
