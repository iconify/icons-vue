<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6hs-wbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-header-sharp" /></template>
<style>
.c6hs-wbwx {
  fill: currentColor;
  d: path("M3 5V3h18v2zm0 16V7h18v14z");
}

</style>
