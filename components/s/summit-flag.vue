<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7jkxrboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:summit-flag" /></template>
<style>
.d7jkxrboz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.75 7.256l3.29 4.524l1.884-2.26q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028q.074-.007.147.001q.074.008.144.03q.071.022.136.057q.064.036.121.083q.126.105.197.254l5 10.5q.032.066.05.138q.018.071.022.145t-.007.147t-.035.143t-.063.133t-.087.118t-.109.099q-.059.044-.126.076q-.153.073-.322.073h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.201.1-.375l7.4-12.826V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.132 0 .256.045l5.5 2q.141.051.251.152t.173.236t.069.284t-.044.289q-.057.157-.175.274t-.274.175l-5.006 1.82zm0-1.827l2.555-.929l-2.555-.929z");
}

</style>
