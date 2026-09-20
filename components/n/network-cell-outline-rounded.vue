<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge45prbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-cell-outline-rounded" /></template>
<style>
.ge45prbyz {
  fill: currentColor;
  d: path("M4.598 21q-.315 0-.488-.204q-.172-.204-.172-.469q0-.143.037-.24t.148-.21L19.877 4.123q.112-.111.21-.148t.24-.036q.265 0 .47.172q.203.172.203.487v15.479q0 .394-.265.659q-.264.264-.658.264zm12.19-1H20V5.427l-3.212 3.212z");
}

</style>
