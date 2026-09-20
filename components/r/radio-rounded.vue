<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-uxh7b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:radio-rounded" /></template>
<style>
.e-uxh7b0q {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V7.842q0-.23.183-.49t.394-.356l10.883-4.44q.176-.068.36.012t.251.257t-.012.36q-.08.184-.257.251L6.031 7h13.354q.69 0 1.153.463T21 8.616v10.769q0 .69-.462 1.153T19.385 21zm4.726-3.234q.62-.62.62-1.497t-.62-1.496t-1.496-.62t-1.496.62t-.62 1.496t.62 1.497t1.496.619t1.496-.62M4 11.54h12.5v-1.347q0-.213.143-.356T17 9.692t.357.144t.143.356v1.347H20V8.616q0-.231-.192-.424T19.385 8H4.615q-.23 0-.423.192T4 8.616z");
}

</style>
