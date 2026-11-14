<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zl9xyybyl"/><path class="q1zitfw2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-shop" /></template>
<style>
.q1zitfw2l {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .13.011.26q.012.129.034.258q.022.128.056.253q.033.126.078.249q.044.122.098.24t.12.231q.064.113.139.22q.074.107.157.207t.175.192q.091.093.19.177t.206.159t.218.142t.23.121t.239.102q.122.045.247.08q.126.035.254.058m2.533-.7q.239-.211.429-.468q.189-.256.321-.547q.131-.291.198-.603T15 9q0 .177.021.352q.021.176.062.348t.102.338t.142.323t.178.305t.213.282t.245.254t.273.224m4.131-.582q.152-.197.271-.415q.118-.219.199-.454t.122-.481T21 9M6.5 20.5v-5h4v5m7.5 1v-4c-.25-2.25-1.75-3.5-3.75-3.5c0 2 1.5 3.5 3.75 3.5c.25-2.5 1.75-4 3.75-4c0 2.25-1.5 4-3.75 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zl9xyybyl {
  d: path("m3 9l1.5-5h15L21 9M4.5 11v9.5H12");
}

</style>
