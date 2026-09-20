<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7sg5vbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-medium-outline-sharp" /></template>
<style>
.e7sg5vbmf {
  fill: currentColor;
  d: path("M3 19v-6h8v6zm10 0v-6h8v6zM3 11V5h18v6zm2 6h4v-2H5zm10 0h4v-2h-4zm2-1");
}

</style>
