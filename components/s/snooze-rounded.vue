<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufuo1-b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:snooze-rounded" /></template>
<style>
.ufuo1-b0n {
  fill: currentColor;
  d: path("m11.008 14.727l3.079-3.461q.005-.006.105-.274v-.323q0-.19-.126-.316q-.125-.126-.316-.126h-3.5q-.19 0-.316.126t-.126.316t.126.316q.126.127.316.127h2.792l-3.128 3.511q-.006.006-.106.273v.273q0 .19.126.316t.316.126h3.5q.19 0 .316-.126t.126-.316t-.126-.316t-.316-.126zm-2.126 5.647q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626M2.78 7.262q-.16-.16-.16-.354t.16-.354L5.554 3.78q.14-.14.344-.15t.364.15t.16.353q0 .195-.16.354L3.489 7.261q-.141.141-.345.15t-.363-.15m18.438 0q-.16.16-.353.16q-.195 0-.354-.16L17.738 4.49q-.14-.141-.15-.345t.15-.363t.354-.16t.354.16l2.773 2.773q.14.14.15.344t-.15.364");
}

</style>
