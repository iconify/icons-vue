<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xklsbgbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-blocked-12-regular" /></template>
<style>
.xklsbgbho {
  fill: currentColor;
  d: path("M12 6A6 6 0 1 1 0 6a6 6 0 0 1 12 0m-1.5 0a4.5 4.5 0 0 0-.832-2.607L3.393 9.668A4.5 4.5 0 0 0 10.5 6M8.607 2.332a4.5 4.5 0 0 0-6.275 6.275z");
}

</style>
