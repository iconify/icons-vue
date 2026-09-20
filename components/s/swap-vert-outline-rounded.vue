<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mex7d7_4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-vert-outline-rounded" /></template>
<style>
.mex7d7_4r {
  fill: currentColor;
  d: path("M8.97 12.145q-.143-.143-.143-.356V4.902l-2.76 2.76q-.14.14-.331.14q-.192 0-.357-.16q-.165-.165-.165-.356q0-.192.165-.357l3.363-3.363q.131-.131.267-.184q.137-.053.299-.053t.308.053t.276.184l3.389 3.388q.146.146.153.335t-.159.353q-.165.16-.354.163t-.354-.163l-2.74-2.74v6.906q0 .213-.143.347t-.357.134t-.357-.144m5.414 8.454q-.146-.053-.276-.183l-3.389-3.389q-.146-.146-.153-.335t.159-.353q.166-.16.354-.163t.354.163l2.74 2.74v-6.906q0-.213.143-.347t.357-.134t.357.144t.143.356v6.887l2.76-2.76q.14-.14.331-.14q.192 0 .357.16q.166.165.166.356q0 .192-.166.357l-3.363 3.364q-.131.13-.267.183q-.137.053-.299.053t-.308-.053");
}

</style>
