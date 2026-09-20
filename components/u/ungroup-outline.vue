<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bko8d7qgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ungroup-outline" /></template>
<style>
.bko8d7qgx {
  fill: currentColor;
  d: path("m8.7 15.989l-.688-.689l4.8-4.8H8.5v-1h6v6h-1v-4.311zM19 12V5h-7V4h8v8zM5.616 20q-.691 0-1.153-.462T4 18.384V4h1v14.385q0 .23.192.423t.423.192H20v1z");
}

</style>
