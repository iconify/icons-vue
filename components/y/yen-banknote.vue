<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pr7ykubcm"/><path class="xbryag90a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:yen-banknote" /></template>
<style>
.pr7ykubcm {
  fill: currentColor;
  d: path("M2 10v44h60V10zm37.273 24.038a7.17 7.17 0 0 0 4.545 1.629c4.018 0 7.271-3.284 7.271-7.334S47.836 21 43.818 21a7.17 7.17 0 0 0-4.545 1.628v-5.295h15.453v22H39.273zm-14.546 5.295H9.273v-22h15.454zm0-24.75H6.545v27.5h18.182v2.75H3.818v-33h20.909zm12.728 30.253h-10.91V12.75h10.91zm22.727-.003H39.273v-2.75h18.182v-27.5H39.273v-2.75h20.908z");
}

.xbryag90a {
  fill: currentColor;
  d: path("M13.985 26.056v2.034h2.603v2.034h-2.603v2.032h2.603v3.051h1.733v-3.051h2.601v-2.032h-2.601V28.09h2.601v-2.034H18.82l4.089-3.945l-1.102-1.569l-4.352 4.196l-4.352-4.196L12 22.111l4.089 3.945z");
}

</style>
