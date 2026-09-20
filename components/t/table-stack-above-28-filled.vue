<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f6yi30bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-above-28-filled" /></template>
<style>
.f6yi30bue {
  fill: currentColor;
  d: path("M24.25 4.5a.75.75 0 0 0 0-1.5H3.75a.75.75 0 0 0 0 1.5zM3 17v-5a1 1 0 0 1 1-1h5.5v6zm0 4.25V18.5h6.5V25H6.75A3.75 3.75 0 0 1 3 21.25M17 25h-6v-6.5h6zm4.25 0H18.5v-6.5H25v2.75A3.75 3.75 0 0 1 21.25 25M24 11a1 1 0 0 1 1 1v5h-6.5v-6zm-13 6h6v-6h-6z");
}

</style>
