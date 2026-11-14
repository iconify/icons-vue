<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgo3e2b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nuclear-medicine" /></template>
<style>
.cgo3e2b-b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.443 16.312q-.428 3.487 1.425 4.583l.013.008q1.861 1.052 4.666-1.073q.228-.173.453-.359q.225.186.453.359q2.805 2.125 4.666 1.073l.013-.008q1.853-1.096 1.425-4.583q-.035-.288-.085-.58q.274-.101.538-.212q3.24-1.364 3.24-3.52t-3.24-3.52q-.264-.111-.538-.212q.05-.292.085-.58q.428-3.487-1.438-4.591q-1.861-1.052-4.666 1.073q-.228.173-.453.359q-.225-.186-.453-.359q-2.805-2.125-4.679-1.065q-1.853 1.096-1.425 4.583q.035.288.085.58q-.274.101-.538.212Q1.75 9.844 1.75 12t3.24 3.52q.264.111.538.212q-.05.292-.085.58");
}

</style>
