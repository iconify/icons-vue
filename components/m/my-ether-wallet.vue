<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmrpdd7bv"/><path class="nk9b-7bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:my-ether-wallet" /></template>
<style>
.bmrpdd7bv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 18.463a6.463 6.463 0 1 0 0-12.925a6.463 6.463 0 0 0 0 12.925");
}

.ft5dv1b6b {
  fill: none;
}

.nk9b-7bzw {
  fill: var(--svg-color--1896a4, #1896a4);
  d: path("M3 12a9 9 0 0 0 9 9a9 9 0 0 0 9-9a9 9 0 1 0-18 0m9 5.656c-3.042 0-5.65-2.467-5.65-5.51c0-.714.135-1.538.382-2.165l2.429 1.035l-.03.128a3 3 0 0 0-.125.73A1 1 0 0 0 9 12.02l.003.033a2.982 2.982 0 0 0 3.661 2.867l1.38 2.344a5.5 5.5 0 0 1-2.042.39m5.213-3.417l-6.162-2.61l3.951-.018c-.14-1.434-1.614-2.598-3.004-2.598c-.315 0-.628.052-.926.155L9.706 6.843A5.5 5.5 0 0 1 12 6.345c3.042 0 5.642 2.512 5.642 5.554c0 .82-.106 1.64-.428 2.34");
}

</style>
