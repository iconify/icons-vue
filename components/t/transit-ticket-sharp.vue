<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmklpcbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transit-ticket-sharp" /></template>
<style>
.dmklpcbqq {
  fill: currentColor;
  d: path("M9.462 16.154h5.077v-.77l-.847-.423q.69 0 1.192-.5q.5-.502.5-1.192V9.461q0-.92-.78-1.306q-.781-.386-2.604-.386q-1.748 0-2.566.408q-.819.408-.819 1.285v3.807q0 .69.501 1.191t1.192.501l-.847.423zm.606-2.222q-.184-.184-.184-.451t.184-.451t.451-.184t.451.184t.184.45t-.184.452t-.45.183t-.452-.183m2.962 0q-.184-.184-.184-.451t.184-.451t.45-.184t.452.184t.184.45t-.184.452t-.451.183t-.451-.183M9.5 12.077V9.461h5v2.616zM3 19v-4.192q.883-.327 1.441-1.088Q5 12.96 5 12t-.559-1.72T3 9.192V5h18v4.192q-.883.327-1.441 1.088Q19 11.04 19 12t.559 1.72T21 14.808V19z");
}

</style>
