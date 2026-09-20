<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5j3nwb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shapes-24-regular" /></template>
<style>
.o5j3nwb9m {
  fill: currentColor;
  d: path("M8.75 3.5A5.25 5.25 0 0 0 8 13.947v1.512A6.751 6.751 0 1 1 15.459 8h-1.512A5.25 5.25 0 0 0 8.75 3.5m3.5 5.5A3.25 3.25 0 0 0 9 12.25v6.5A3.25 3.25 0 0 0 12.25 22h6.5A3.25 3.25 0 0 0 22 18.75v-6.5A3.25 3.25 0 0 0 18.75 9zm-1.75 3.25c0-.966.784-1.75 1.75-1.75h6.5c.966 0 1.75.784 1.75 1.75v6.5a1.75 1.75 0 0 1-1.75 1.75h-6.5a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
