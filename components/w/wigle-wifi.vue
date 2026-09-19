<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ezasasb9a"/><path class="myobd6brk"/><path class="zq_tflbws"/><path class="h__j5ccrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wigle-wifi" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ezasasb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.727 10.49a21.502 21.502 0 0 0-28.96 31.194");
}

.h__j5ccrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.22 10.911l-.294-.994l-2.229-.967l-.169 1.934h-.715l-2.271 1.346v.968l2.839 1.471l1.367-2.859l4.584 2.397l1.977 2.187m-13.08-.253l1.771.253l1.49.589v1.514l1.323.21l.884-1.283m-4.374 1.283L24 16.394");
}

.myobd6brk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.668 10.911l2.187.394l-3.911 6.266v5.552L15.9 28.59l4.1 2.439l4.669 3.533l1.345-.378l.799.378v2.565l-2.229 1.388l-1.051 1.052l.326 2.817l1.819 1.472l-.337 1.644m15.671-8.353h-1.75l-1.136-2.122h-2.355l-.21-1.262l-5.131-.883l-2.733.42l-.884 1.262");
}

.zq_tflbws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.575 33.735s.358-2.58.284-2.706a16.5 16.5 0 0 0-2.303-.42l.757-2.403l-2.27.889l-1.515-1.472v-2.145l1.304-1.711l2.397.41l2.313-.41l1.388 2.384m-1.472 1.303l3.239 1.297m1.43.68l2.186.252m-6.771-5.916l3.659-2.074l-.294-2.145l2.061-.715l-.547-.673l1.892-.925h2.019l-2.229-.841l1.388-1.262h1.677M21.43 7.857l.589 1.261h.925l1.598-.967l3.155.799l1.853-2.254m9.197 2.574l-2.092 1.11l.168 2.691l-.715.463l-3.323-3.196l-1.472-2.103h-3.028");
}

</style>
