<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6hfftocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:space-dashboard-2-outline-sharp" /></template>
<style>
.a6hfftocs {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h8V5H5zm10 0h4v-6h-4zm0-8h4V5h-4z");
}

</style>
