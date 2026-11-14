<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpgbi-7ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shelf-bin-label" /></template>
<style>
.fpgbi-7ui {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.367 3.097l-3.5 5.5q-.08.126-.106.273t.007.293q.045.204.189.355q-.207.512-.207 1.232v9q0 1.036.732 1.768t1.768.732h12q.641 0 1.165-.28q.078.096.182.163q.063.039.132.066q.068.027.141.04q.073.012.147.011t.146-.018q.072-.016.139-.046t.128-.072t.112-.096q.051-.053.091-.115l3.5-5.5q.117-.185.117-.403V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H6q-.095 0-.186.024q-.092.023-.175.069q-.083.045-.152.11t-.12.144m12.044 5.431q-.523-.278-1.161-.278h-12q-.206 0-.395.017L6.412 4.25h13.722zm3.339 7.254l-2 3.142V10.75q0-.641-.28-1.165q.096-.078.163-.182l2.117-3.327zM14 11.5q.932 0 1.591.659t.659 1.591v3q0 .932-.659 1.591T14 19H6.5q-2.25 0-2.25-2.25v-3q0-2.25 2.25-2.25z");
}

</style>
