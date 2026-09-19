<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r75uvjn9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-square" /></template>
<style>
.r75uvjn9u {
  fill: currentColor;
  d: path("M20 4H4v16h16zm-2 14H6V6h12z");
}

</style>
