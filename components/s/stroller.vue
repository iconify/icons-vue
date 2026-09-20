<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ar-oc8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stroller" /></template>
<style>
.h7ar-oc8k {
  fill: currentColor;
  d: path("M13.722 19.932q-.414-.415-.414-1.009t.414-1.008t1.009-.415t1.009.415t.414 1.008t-.415 1.009t-1.008.414t-1.009-.414m-6.76.414q-.575 0-1-.414t-.423-1.009t.424-1.008t.999-.415q.613 0 1.018.415q.404.414.404 1.008t-.404 1.009t-1.018.414m.463-3.846q-.323 0-.451-.287q-.128-.286.086-.536l8.679-10.175q.442-.518.939-.76t1.107-.242q.88 0 1.48.6t.6 1.48V7h-1v-.42q0-.459-.31-.77q-.31-.31-.77-.31q-.39 0-.68.148t-.541.425l-1.41 1.644v7.168q0 .67-.472 1.143q-.472.472-1.144.472zm2.81-6.842L6.34 5.764q.95-.639 1.987-.951t2.192-.313q.895 0 1.742.179t1.75.555z");
}

</style>
