<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7uifmb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:menu-outline-sharp" /></template>
<style>
.e7uifmb1n {
  fill: currentColor;
  d: path("M3 18v-2h18v2zm0-5v-2h18v2zm0-5V6h18v2z");
}

</style>
