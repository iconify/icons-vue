<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kprzxlbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-full-outline-sharp" /></template>
<style>
.kprzxlbgw {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h1V6H4zm3 0h10V6H7zm12 0h1V6h-1zM7 6v12z");
}

</style>
