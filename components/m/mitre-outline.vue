<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqr_fztl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mitre-outline" /></template>
<style>
.pgqr_fztl {
  fill: currentColor;
  d: path("M13.77 14.116V9.885h2.115v-3.77h-2.116v-4.23H19v4.23h-2.116v3.77H19v4.23zm1-1H18v-2.231h-3.23zm0-8H18V2.885h-3.23zm-9.77 17v-4.232h2.116v-3.768H5V9.885h2.116v-3.77H5v-4.23h5.23v4.23H8.117v3.77h2.115v4.23H8.116v3.77h2.115v4.23zm1-1h3.23v-2.231H6zm0-8h3.23v-2.231H6zm0-8h3.23V2.885H6zM7.616 4");
}

</style>
