<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwbsg33ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-none" /></template>
<style>
.pwbsg33ee {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm20-4H5v18h18zm-2 16H7V3h14z");
}

</style>
