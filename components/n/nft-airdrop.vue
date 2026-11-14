<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-kwjngv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nft-airdrop" /></template>
<style>
.u8-kwjngv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 9.499q.002-3.252 2.764-5.526Q8.211 1.752 12 1.752t6.486 2.221Q21.249 6.247 21.25 9.5l-.001.046l-.001.004q-.009.136-.065.26t-.152.22q-.018.018-.037.034l-4 3.5q-.073.064-.16.107q.416.769.416 1.954v3.25q0 3.375-3.375 3.375h-3.75q-3.375 0-3.375-3.375v-3.25q0-1.185.416-1.954q-.087-.043-.16-.107l-4-3.5q-.024-.02-.046-.043q-.099-.103-.154-.235q-.046-.114-.054-.236zm9.536.695q-.138.056-.286.056t-.286-.056q-3.377-1.391-6.753-.413l3.033 2.655q.111.097.177.23q.769-.416 1.954-.416h3.75q1.185 0 1.954.416q.066-.133.177-.23l3.033-2.655q-3.376-.978-6.753.413M9.75 17.25q0 2.25 2.25 2.25t2.25-2.25T12 15t-2.25 2.25");
}

</style>
