<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsap39ajz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quick-reference-sharp" /></template>
<style>
.dsap39ajz {
  fill: currentColor;
  d: path("M15.923 19h.77v-3h-.77zm.385-3.827q.161.02.273-.102q.111-.121.111-.283t-.12-.273t-.264-.111q-.162 0-.274.111q-.111.112-.111.273q0 .143.111.264q.112.121.274.121m-2.836 4.355q-1.164-1.164-1.164-2.836q0-1.67 1.164-2.835t2.836-1.165q1.67 0 2.835 1.165t1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164M13 8h4l-4-4l4 4l-4-4zM4 21V3h9.5L18 7.5v3.03q-.423-.13-.836-.176q-.414-.046-.856-.046q-1.445 0-2.688.585T11.504 12.5H7.5v1h3.29q-.378.667-.605 1.427T9.94 16.5H7.5v1h2.479q.137.971.546 1.865T11.605 21z");
}

</style>
