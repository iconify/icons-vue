<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdp8lvdur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-plus-minus" /></template>
<style>
.bdp8lvdur {
  fill: currentColor;
  d: path("M18 10.998h-5v5a1 1 0 0 1-2 0v-5H6a1 1 0 0 1 0-2h5v-5a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2m0 10H6a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2");
}

</style>
