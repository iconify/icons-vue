<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nkq17hlzv"/><path class="lskqnybnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-refund-desk" /></template>
<style>
.lskqnybnz {
  d: path("M12.855 12.718q.188-.118.36-.258t.324-.301t.284-.34t.238-.372q.108-.194.19-.4t.138-.421q.055-.214.083-.434t.028-.442q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T11 6.25t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T7.5 9.75t.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05t.343.017q.438 0 .862-.108q.425-.108.809-.317M7.5 9.75h7M8 16.5h4.7m2.05 4.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.nkq17hlzv {
  d: path("M11.1 21.5H4v-19h14v10.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
