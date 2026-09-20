<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwhxpyw6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stroller-rounded" /></template>
<style>
.hwhxpyw6a {
  fill: currentColor;
  d: path("M13.722 19.928q-.414-.418-.414-1.005t.414-1.005t1.009-.418t1.009.418t.414 1.005t-.415 1.005t-1.008.418t-1.009-.418m-6.76.418q-.575 0-1-.418q-.423-.418-.423-1.005t.424-1.005t.999-.418q.613 0 1.018.418t.404 1.005t-.404 1.005t-1.018.418m.463-3.846q-.32 0-.45-.287t.085-.536l8.679-10.175q.442-.518.939-.76t1.107-.242q.88 0 1.48.6t.6 1.49v.016q0 .212-.143.356t-.357.144t-.356-.144t-.143-.356v-.02q0-.463-.31-.775q-.311-.311-.771-.311q-.381 0-.675.148t-.546.425l-1.41 1.644v7.162q0 .677-.474 1.149t-1.14.472zm2.81-6.842L6.967 6.39q-.248-.249-.197-.575t.353-.499q.789-.396 1.626-.606q.838-.211 1.77-.211q.895 0 1.742.179t1.75.556z");
}

</style>
