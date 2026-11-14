<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r82b84bgs"/><path class="kgsjbjmpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:washing-machine-smart" /></template>
<style>
.kgsjbjmpf {
  d: path("M13.748 13.357q.002-.053.002-.107q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05t-.343-.017t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34t-.017.343t.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147t.323.115t.333.084q.169.033.34.05t.343.017q.669 0 1.291-.247M18.5 20.75h.01M16.5 18.5a2.75 2.75 0 0 1 4 0M15 16a5 5 0 0 1 7 0");
}

.r82b84bgs {
  d: path("M14 20H3V2.5h15v9.3M3 7h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
