<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvo6x8-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stroller-outline" /></template>
<style>
.jdvo6x8-n {
  fill: currentColor;
  d: path("M13.722 19.928q-.414-.418-.414-1.005t.414-1.005t1.009-.418t1.009.418t.414 1.005t-.415 1.005t-1.008.418t-1.009-.418m-6.76.418q-.575 0-1-.418q-.423-.418-.423-1.005t.424-1.005t.999-.418q.613 0 1.018.418t.404 1.005t-.404 1.005t-1.018.418m1.58-4.846h4.997q.269 0 .442-.173t.173-.442v-5.96zm-1.117 1q-.32 0-.45-.287t.085-.536l8.679-10.175q.442-.518.939-.76t1.107-.242q.88 0 1.48.6t.6 1.488V7h-1v-.42q0-.46-.31-.77t-.77-.31q-.381 0-.675.148t-.546.425l-1.41 1.644v7.162q0 .677-.474 1.149t-1.14.472zm2.81-6.842L6.34 5.764q.95-.639 1.987-.951t2.192-.313q.895 0 1.742.179t1.75.555zm-.068-1.47l2.087-2.446q-.431-.12-.867-.182q-.437-.06-.868-.06q-.654 0-1.28.123t-1.235.383zm0 0");
}

</style>
