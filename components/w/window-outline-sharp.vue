<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5e7sbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-outline-sharp" /></template>
<style>
.iu5e7sbjl {
  fill: currentColor;
  d: path("M21 21H3V3h18zm-8-8v6h6v-6zm0-2h6V5h-6zm-2 0V5H5v6zm0 2H5v6h6z");
}

</style>
