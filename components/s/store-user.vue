<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8hv_vbbm"/><path class="d4n2gq12x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-user" /></template>
<style>
.c8hv_vbbm {
  d: path("m3 9l1.5-5h15L21 9M4.5 11v9.5h7.1");
}

.d4n2gq12x {
  d: path("M3 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253t.175.236t.198.218t.218.198t.236.175t.253.152t.266.126t.277.099t.286.071q.144.029.291.044T6 12q.147 0 .294-.014t.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198t.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286q.029-.144.044-.291T9 9q0 .147.014.294t.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 12 12 12t.294-.014q.147-.015.291-.044q.145-.028.286-.071t.277-.099t.266-.126t.253-.152q.122-.081.236-.175t.218-.198q.105-.104.198-.218t.175-.236t.152-.253t.126-.266t.099-.277t.071-.286t.044-.291Q15 9.147 15 9q0 .328.071.647q.07.32.208.617q.139.298.338.558q.198.26.449.471m3.85.016q.254-.212.457-.473q.202-.262.342-.561t.213-.622Q21 9.331 21 9M6.5 20.5v-5h4v5m5.5-4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
