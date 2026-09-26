<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb30fqvcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-24-regular" /></template>
<style>
.qb30fqvcr {
  fill: currentColor;
  d: path("M14.25 2a.75.75 0 1 1 0 1.5h-1.5v17h1.5a.75.75 0 1 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-17h-1.5a.75.75 0 0 1 0-1.5zm-4 4.5h-5A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75h5V19h-5A3.25 3.25 0 0 1 2 15.75v-7.5A3.25 3.25 0 0 1 5.25 5h5zm8.5-1.5A3.25 3.25 0 0 1 22 8.25v7.5A3.25 3.25 0 0 1 18.75 19h-5v-1.5h5a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75h-5V5z");
}

</style>
