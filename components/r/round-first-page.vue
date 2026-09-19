<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks_hw9b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-first-page" /></template>
<style>
.ks_hw9b_n {
  fill: currentColor;
  d: path("M17.7 15.89L13.82 12l3.89-3.89A.996.996 0 1 0 16.3 6.7l-4.59 4.59a.996.996 0 0 0 0 1.41l4.59 4.59c.39.39 1.02.39 1.41 0a.993.993 0 0 0-.01-1.4M7 6c.55 0 1 .45 1 1v10c0 .55-.45 1-1 1s-1-.45-1-1V7c0-.55.45-1 1-1");
}

</style>
