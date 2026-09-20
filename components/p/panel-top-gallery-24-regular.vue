<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug8w1fywr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-top-gallery-24-regular" /></template>
<style>
.ug8w1fywr {
  fill: currentColor;
  d: path("M5.25 4A3.25 3.25 0 0 0 2 7.25v9.5A3.25 3.25 0 0 0 5.25 20h13.5A3.25 3.25 0 0 0 22 16.75v-9.5A3.25 3.25 0 0 0 18.75 4zM3.5 7.25c0-.966.784-1.75 1.75-1.75H8v5H3.5zm0 4.75h17v4.75a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75zm17-1.5H16v-5h2.75c.966 0 1.75.784 1.75 1.75zm-6-5v5h-5v-5z");
}

</style>
