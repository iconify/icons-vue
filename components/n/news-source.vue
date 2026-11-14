<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0no0pb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:news-source" /></template>
<style>
.l0no0pb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.038 9.239q.227-.397.344-.839q.118-.443.118-.9q0-.172-.017-.343t-.05-.34t-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294q-.095-.143-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T9 4t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177q-.143.095-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333t-.05.34Q5.5 7.328 5.5 7.5t.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05T9 11q.299 0 .593-.051q.295-.05.577-.15t.542-.246t.493-.335M2.5 21.5c0-4 2.75-6.5 6.5-6.5a7.5 7.5 0 0 1 2.226.325M14 12h5l2.5 2.5V21H14Z");
}

</style>
