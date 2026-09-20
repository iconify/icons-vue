<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc3nk7bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-bus-24-filled" /></template>
<style>
.wc3nk7bxf {
  fill: currentColor;
  d: path("M10.75 5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zM4 5.75A3.75 3.75 0 0 1 7.75 2h8.5A3.75 3.75 0 0 1 20 5.75V9.5h1.227a.75.75 0 0 1 0 1.5H20v8.75a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 15 19.75V18.5H9v1.25a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 4 19.75V11H2.75a.75.75 0 0 1 0-1.5H4zM16.5 18.5v1.25c0 .138.112.25.25.25h1.5a.25.25 0 0 0 .25-.25V18.5zm-11 0v1.25c0 .138.112.25.25.25h1.5a.25.25 0 0 0 .25-.25V18.5zm2.25-15A2.25 2.25 0 0 0 5.5 5.75V12h13V5.75a2.25 2.25 0 0 0-2.25-2.25zM9 15a1 1 0 1 0-2 0a1 1 0 0 0 2 0m7 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
