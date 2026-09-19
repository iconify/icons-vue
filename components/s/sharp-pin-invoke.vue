<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_k29fntd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pin-invoke" /></template>
<style>
.l_k29fntd {
  fill: currentColor;
  d: path("M22 12v8H2V4h12v2H4v12h16v-6zm0-5c0-1.66-1.34-3-3-3s-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3m-10.53 5.12l-2.83 2.83l1.41 1.41l2.83-2.83L15 15.66V10H9.34z");
}

</style>
