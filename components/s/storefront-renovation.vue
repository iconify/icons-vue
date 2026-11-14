<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_juueb9v"/><path class="d92xk5b0m"/><path class="vfitrb0qa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:storefront-renovation" /></template>
<style>
.d92xk5b0m {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .184.022.366q.023.182.067.36t.11.35t.152.333t.192.312t.228.287t.262.257q.138.12.291.223m3.333.013q.154-.102.295-.223q.14-.12.265-.257q.125-.136.231-.287q.107-.152.195-.315t.154-.335q.067-.173.112-.352q.046-.18.068-.363Q21 9.185 21 9M6.5 20.5v-5h4v5m5.125-6.25h3.5a1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 19.125 17h-3.5a1.375 1.375 0 0 1-1.375-1.375a1.375 1.375 0 0 1 1.375-1.375");
}

.h_juueb9v {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.5m-15-.5v9.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfitrb0qa {
  d: path("M20.5 15.5h1.25v2.75H18v1.25m0 0V22");
}

</style>
