<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlidhsbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-edit-off" /></template>
<style>
.zlidhsbtd {
  fill: currentColor;
  d: path("m14.06 9.02l.92.92l-1.11 1.11l1.41 1.41l2.52-2.52l-3.75-3.75l-2.52 2.52l1.41 1.41zm6.65-1.98a.996.996 0 0 0 0-1.41l-2.34-2.34c-.2-.2-.45-.29-.71-.29s-.51.1-.7.29l-1.83 1.83l3.75 3.75zM2.81 2.81L1.39 4.22l7.32 7.32L3 17.25V21h3.75l5.71-5.71l7.32 7.32l1.41-1.41zM5.92 19H5v-.92l5.13-5.13l.92.92z");
}

</style>
