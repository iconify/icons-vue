<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_xkbobac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-lamp" /></template>
<style>
.u_xkbobac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5a7.5 7.5 0 0 1 15 0Zm7.5 0v6.6m0 .3v1.1m3.425 2.383q.075.305.075.617H7q0-.147.017-.294t.05-.291q.034-.145.084-.286t.115-.277t.147-.266t.177-.253t.204-.236q.11-.114.231-.218q.122-.105.255-.198t.276-.175t.294-.152t.311-.126t.323-.099t.333-.071t.34-.044t.343-.014q.67 0 1.293.212m2.457-1.462a5.3 5.3 0 0 1 7.5 0M16 19a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

</style>
