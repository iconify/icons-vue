<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zl9xyybyl"/><path class="iinzuxbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:under-new-management" /></template>
<style>
.iinzuxbkp {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .273.049.541q.05.269.146.524q.097.255.239.489q.141.233.322.437m4.242.247q.236-.211.423-.467t.317-.545t.196-.599T21 9M6.5 20.5v-5h4v.8m0 2.9v1.3m6.75-5.75l.884 2.116l2.116.884l-2.116.884l-.884 2.116l-.884-2.116l-2.116-.884l2.116-.884ZM21 14v2m-1-1h2");
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
