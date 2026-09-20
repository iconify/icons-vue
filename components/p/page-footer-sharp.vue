<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv1m3q_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-footer-sharp" /></template>
<style>
.kyv1m3q_x {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V3h18v14z");
}

</style>
