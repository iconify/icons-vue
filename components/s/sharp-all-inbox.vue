<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a41i4vgpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-all-inbox" /></template>
<style>
.a41i4vgpb {
  fill: currentColor;
  d: path("M21 3H3v11h18zm-2 6h-4c0 1.62-1.38 3-3 3s-3-1.38-3-3H5V5h14zm-4 7h6v5H3v-5h6c0 1.66 1.34 3 3 3s3-1.34 3-3");
}

</style>
