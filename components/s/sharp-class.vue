<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uydn-q5_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-class" /></template>
<style>
.uydn-q5_t {
  fill: currentColor;
  d: path("M20 2H4v20h16zM6 4h5v8l-2.5-1.5L6 12z");
}

</style>
