<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3fq5ybos"/><path class="t1sr0_buq"/><path class="vfitrb0qa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:storefront-renovation" /></template>
<style>
.t1sr0_buq {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .13.011.26q.012.129.034.258q.022.128.056.253q.033.126.078.249q.044.122.098.24t.12.231q.064.113.139.22q.074.107.157.207t.175.192q.091.093.19.177t.206.159t.218.142t.23.121t.239.102q.122.045.247.08q.126.035.254.058m2.28-.499q.146-.104.279-.224t.251-.255t.219-.284t.183-.308t.145-.327t.106-.342q.042-.174.064-.353Q15 9.179 15 9q0 .184.022.366q.023.182.067.36t.11.35t.152.333t.192.312t.228.287t.262.257q.138.12.291.223m3.421-.048q.145-.104.277-.224t.248-.255t.217-.283q.099-.147.181-.306t.144-.326t.104-.34t.063-.351T21 9M6.5 20.5v-5h4v5m3.75-6.25h6.25V17h-6.25Z");
}

.t3fq5ybos {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.4m-15-.4v9.5H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfitrb0qa {
  d: path("M20.5 15.5h1.25v2.75H18v1.25m0 0V22");
}

</style>
