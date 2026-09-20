<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jak7gbm-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-rounded" /></template>
<style>
.jak7gbm-m {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm6.596-3.462l-1.427-1.725q-.131-.142-.314-.142q-.182 0-.313.162l-1.154 1.52q-.162.213-.05.43t.354.217h7.538q.243 0 .354-.217t-.03-.43l-2.02-2.712q-.13-.162-.323-.162q-.192 0-.323.162z");
}

</style>
