<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f03cuk58l"/><path class="jnqq21v7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-entrance" /></template>
<style>
.f03cuk58l {
  d: path("M13.17 20.099q-.232.082-.474.131t-.488.064q-.247.015-.493-.005t-.486-.075q-.241-.054-.472-.142t-.447-.207t-.413-.267t-.372-.323l-4.8-4.8q-.122-.122-.231-.255q-.109-.132-.204-.275q-.096-.143-.177-.295t-.147-.311q-.066-.158-.116-.323q-.049-.164-.083-.333t-.05-.34Q3.7 12.172 3.7 12t.017-.343t.05-.34t.083-.333t.116-.323t.147-.311t.177-.295t.204-.275q.109-.133.231-.255l4.8-4.8q.122-.122.255-.231q.132-.109.275-.204q.143-.096.295-.177t.311-.147q.158-.066.323-.116q.164-.049.333-.083t.34-.05Q11.828 3.7 12 3.7t.343.017t.34.05t.333.083t.323.116t.311.147t.295.177t.275.204q.133.109.255.231l4.8 4.8q.104.104.198.215q.095.112.179.231q.085.12.16.246q.074.126.138.257q.064.132.117.269q.052.136.093.277t.07.284t.047.289q.017.145.021.292q.005.146-.002.292q-.008.146-.027.292q-.02.145-.051.288q-.032.143-.076.282q-.043.14-.098.276q-.055.135-.121.266t-.143.255");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnqq21v7p {
  d: path("M9.75 16.5v-9H12a2.75 2.75 0 0 1 0 5.5H9.75M21 18h-6m2.5-2.5L15 18l2.5 2.5");
}

</style>
