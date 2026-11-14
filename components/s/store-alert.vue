<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bnzd_77ll"/><path class="kv79g241o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-alert" /></template>
<style>
.bnzd_77ll {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.4m-15-.4v9.5h7.2");
}

.kv79g241o {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .177.021.352q.021.176.062.348t.102.338t.142.323t.178.305t.213.282t.245.254t.273.224m3.509.014q.145-.104.277-.224t.248-.255t.217-.283q.099-.147.181-.306t.144-.326t.104-.34t.063-.351T21 9M6.5 20.5v-5h4v5M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-2.25v2.75m0 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
