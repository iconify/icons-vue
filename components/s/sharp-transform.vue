<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2xd-cbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-transform" /></template>
<style>
.z2xd-cbcc {
  fill: currentColor;
  d: path("M22 18v-2H8V4h2L7 1L4 4h2v2H2v2h4v10h10v2h-2l3 3l3-3h-2v-2zM10 8h6v6h2V6h-8z");
}

</style>
