<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b95ywj-gj"/><path class="r7j7yibag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-star" /></template>
<style>
.b95ywj-gj {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.3m-15-.3v9.5H12");
}

.r7j7yibag {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .314.065.621t.192.594t.311.542q.184.254.417.465m3.672.279q.154-.102.295-.223q.14-.12.265-.257q.125-.136.231-.287q.107-.152.195-.315t.154-.335q.067-.173.112-.352q.046-.18.068-.363Q21 9.185 21 9M6.5 20.5v-5h3m1 1v4m7.25-6.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
