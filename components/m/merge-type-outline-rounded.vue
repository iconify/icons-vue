<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubwtpkwas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:merge-type-outline-rounded" /></template>
<style>
.ubwtpkwas {
  fill: currentColor;
  d: path("M16.975 18.796q-.204-.01-.344-.15l-4.646-4.652q-.218-.217-.351-.522q-.134-.305-.134-.628V5.952l-2.74 2.74q-.166.166-.357.166t-.357-.166q-.165-.165-.155-.363q.009-.198.155-.345l3.389-3.394q.13-.13.267-.183T12 4.354t.298.053t.268.183l3.388 3.383q.165.166.165.357t-.165.357t-.366.158t-.347-.153L12.5 5.952v6.898q0 .116.039.221t.134.202l4.666 4.666q.159.159.159.353t-.16.354t-.363.15m-10.314-.144q-.165-.165-.152-.367t.152-.34l2.872-2.878q.146-.146.347-.155t.366.155t.163.357t-.169.357l-2.87 2.871q-.16.16-.355.16t-.353-.16");
}

</style>
