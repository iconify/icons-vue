<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0lek7aev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-call-end" /></template>
<style>
.e0lek7aev {
  fill: currentColor;
  d: path("m3.68 16.07l3.92-3.11V9.59c2.85-.93 5.94-.93 8.8 0v3.38l3.91 3.1L24 12.39c-6.41-7.19-17.59-7.19-24 0z");
}

</style>
