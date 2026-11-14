<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4q9t1sev"/><path class="du2dsefgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visual-regression" /></template>
<style>
.du2dsefgv {
  fill: currentColor;
  d: path("M14 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4q9t1sev {
  d: path("M3 5.5v12q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T5 19.5h2.872m-.774-3.954q-.26-.246-.465-.539q-.205-.292-.347-.621q-.141-.328-.214-.678Q6 13.358 6 13V6q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323t.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084q.169-.033.34-.05T9.5 2.5h5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T18 6v5.042M9.5 17c1.5-2.25 3.5-3.5 6-3.5s4.5 1.25 6 3.5c-1.5 2.25-3.5 3.5-6 3.5s-4.5-1.25-6-3.5");
}

</style>
