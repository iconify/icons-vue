<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0eyarpbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-lamp" /></template>
<style>
.l0eyarpbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5a7.5 7.5 0 0 1 15 0Zm7.5 0v8m3.4 2.288q.1.351.1.712H7q0-.147.017-.294t.05-.291q.034-.145.084-.286t.115-.277t.147-.266t.177-.253q.095-.122.204-.236q.11-.114.231-.218q.122-.105.255-.198t.276-.175t.294-.152t.311-.126t.323-.099t.333-.071t.34-.044t.343-.014q.725 0 1.391.247m2.359-1.497a5.3 5.3 0 0 1 7.5 0M16 19a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

</style>
