<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":266};
const content = `<path class="vdc83cbgo"/><path class="evudg-y2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vagrant-icon" /></template>
<style>
.evudg-y2i {
  fill: var(--svg-color--127eff, #127eff);
  d: path("m221.102 0l-58.143 34.105h-.044v23.281l-34.933 81.596v27.257l-23.249 13.518l-46.54-104.965V54.25l34.938-20.101L34.9 0L0 20.41v25.004l78.564 191.067l49.412 28.583v-71.788l23.293-13.519l-.31-.176l46.85-104.789V54.25l58.187-33.84z");
}

.vdc83cbgo {
  fill: var(--svg-color--1159cc, #1159cc);
  d: path("m221.102 0l34.894 20.41l-58.187 33.84v.04l58.187-33.88v24.253L177.863 236.26l-49.887 28.8v.004l-.003-.003l-.002.003l-.001-.004l-49.406-28.579L0 45.414V20.41L34.9 0l58.231 34.149l-.199.114l.155.063v23.06l34.889 81.596v27.26l.006-.003v-27.257l34.933-81.596V34.105h.044zM71.579 46.548L58.193 54.25l-.001.04z");
}

</style>
