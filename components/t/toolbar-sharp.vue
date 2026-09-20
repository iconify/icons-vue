<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh5k6c_dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toolbar-sharp" /></template>
<style>
.vh5k6c_dg {
  fill: currentColor;
  d: path("M3 8V3h18v5zm0 13V10h18v11z");
}

</style>
