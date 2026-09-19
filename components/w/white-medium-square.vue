<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ueq0-m88d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-medium-square" /></template>
<style>
.ueq0-m88d {
  fill: currentColor;
  d: path("M54 10v44H10V10zm2-2H8v48h48z");
}

</style>
