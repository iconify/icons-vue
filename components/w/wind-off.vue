<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htwmjzb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wind-off" /></template>
<style>
.htwmjzb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h2.6m7.8 0H14q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236q.082-.123.152-.253t.126-.266t.099-.277t.071-.286t.044-.291T17 6q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277q-.057-.136-.126-.266q-.07-.13-.152-.253q-.081-.122-.175-.236t-.198-.218t-.218-.198t-.236-.175t-.253-.152q-.13-.069-.266-.126t-.277-.099t-.286-.071t-.291-.044Q14.147 3 14 3t-.294.014t-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152t-.236.175t-.218.198t-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286q-.029.144-.044.291T11 6m-8.5 7h6.6m7.8 0h1.6q.135 0 .27.013q.134.013.266.04q.133.026.262.065q.13.04.254.091q.125.052.244.116q.119.063.232.138q.112.076.217.161q.104.086.2.181q.095.096.181.2t.161.217t.138.232t.116.244q.051.124.091.254q.039.129.065.262q.027.132.04.266q.013.135.013.27q0 .323-.075.637t-.22.603M2.5 17h7m-6-13.5l17 17");
}

</style>
