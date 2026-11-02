<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzl9v9h9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-fill-sharp" /></template>
<style>
.bzl9v9h9e {
  fill: currentColor;
  d: path("M15.171 7H7v4h11a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H8.829a3 3 0 1 1 0-2H17v-4H6a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h9.171a3 3 0 1 1 0 2");
}

</style>
