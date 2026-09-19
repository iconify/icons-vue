<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lwkacpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-minus" /></template>
<style>
.r_lwkacpr {
  fill: currentColor;
  d: path("M18 12.998H6a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2");
}

</style>
