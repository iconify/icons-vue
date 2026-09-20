<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzh7dfb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-full-sharp" /></template>
<style>
.nzh7dfb0m {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h1V6H4zm15 0h1V6h-1z");
}

</style>
