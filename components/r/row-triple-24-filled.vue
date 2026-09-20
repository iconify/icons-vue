<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq0ub4wnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:row-triple-24-filled" /></template>
<style>
.wq0ub4wnb {
  fill: currentColor;
  d: path("M5.75 2.02A1.75 1.75 0 0 0 4 3.77v2.5c0 .966.784 1.75 1.75 1.75h12.5A1.75 1.75 0 0 0 20 6.27v-2.5a1.75 1.75 0 0 0-1.75-1.75zm0 7A1.75 1.75 0 0 0 4 10.77v2.5c0 .966.784 1.75 1.75 1.75h12.5A1.75 1.75 0 0 0 20 13.27v-2.5a1.75 1.75 0 0 0-1.75-1.75zm0 7A1.75 1.75 0 0 0 4 17.77v2.5c0 .966.784 1.75 1.75 1.75h12.5A1.75 1.75 0 0 0 20 20.27v-2.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
