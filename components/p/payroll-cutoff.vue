<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ekthxob1r"/><path class="a3lzl6nie"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-cutoff" /></template>
<style>
.a3lzl6nie {
  d: path("M13.718 11.96q.148-.104.282-.224q.135-.12.254-.256q.119-.135.221-.284t.185-.309t.147-.329t.107-.344t.064-.354T15 9.5q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277t-.126-.266t-.152-.253q-.081-.122-.175-.236t-.198-.218t-.218-.198t-.236-.175t-.253-.152q-.13-.069-.266-.126t-.277-.099q-.141-.043-.286-.071q-.144-.029-.291-.044T12 6.5t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099q-.136.057-.266.126q-.13.07-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236q-.082.123-.152.253t-.126.266t-.099.277t-.071.286t-.044.291T9 9.5q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044q.147.014.294.014q.342 0 .676-.077M15.5 14.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.ekthxob1r {
  d: path("M12.7 15.5H2.5v-12h19v8.4");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
