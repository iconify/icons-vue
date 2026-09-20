<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1f9sub4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:slab-serif-outline-sharp" /></template>
<style>
.i1f9sub4j {
  fill: currentColor;
  d: path("M5.942 18h4.574v-.942H8.033l1.16-3h5.446l1.153 3H13.36V18h4.698v-.942h-1.154L12.566 6h-1.222L7 17.058H5.942zm3.606-4.856l2.335-5.963h.098l2.296 5.963zM3 21V3h18v18zm1-1h16V4H4zm0 0V4z");
}

</style>
