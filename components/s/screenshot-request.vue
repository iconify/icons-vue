<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-oiabbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screenshot-request" /></template>
<style>
.vb-oiabbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V5a2 2 0 0 1 2-2h3m8 0h3a2 2 0 0 1 2 2v3M3 16v3a2 2 0 0 1 2 2h3m5.813-8.957Q14 11.538 14 11q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277t-.126-.266t-.152-.253q-.081-.122-.175-.236t-.198-.218q-.104-.105-.218-.198t-.236-.175t-.253-.152t-.266-.126t-.277-.099t-.286-.071t-.291-.044Q11.147 8 11 8t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286t-.044.291Q8 10.853 8 11t.014.294q.015.147.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q10.853 14 11 14q.182 0 .363-.022q.18-.022.357-.066q.177-.043.347-.108t.331-.15t.311-.188q.149-.104.285-.225t.256-.257q.121-.137.224-.287M15.75 15a2.25 2.25 0 1 1 3 2.25q-.75.375-.75 1.5m0 2.75h.01");
}

</style>
