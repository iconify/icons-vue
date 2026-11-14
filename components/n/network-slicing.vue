<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va4jpem_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:network-slicing" /></template>
<style>
.va4jpem_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.654 3.25h13.442q1.08-.001 1.675.901q.594.902.168 1.895l-.295.688q-.649 1.516-2.298 1.516H4.904q-1.08.001-1.675-.901q-.594-.902-.168-1.895l.295-.688Q4.005 3.25 5.654 3.25m13.442 6.5H5.654q-1.649 0-2.298 1.516l-.295.688q-.426.993.168 1.895q.595.902 1.675.901h13.442q1.649 0 2.298-1.516l.295-.688q.426-.993-.168-1.895q-.595-.902-1.675-.901m-13.442 6.5h13.442q1.08-.001 1.675.901q.594.902.168 1.895l-.295.688q-.649 1.516-2.298 1.516H4.904q-1.08.001-1.675-.901q-.594-.902-.168-1.895l.295-.688q.649-1.516 2.298-1.516");
}

</style>
