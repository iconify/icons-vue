<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f48o6q92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-countertops" /></template>
<style>
.f48o6q92l {
  fill: currentColor;
  d: path("M22 10h-4V7c0-1.66-1.34-3-3-3s-3 1.34-3 3h2c0-.55.45-1 1-1s1 .45 1 1v3H8c1.1 0 2-.9 2-2V4H4v4c0 1.1.9 2 2 2H2v2h2v8h16v-8h2zM6 6h2v2H6zm0 12v-6h5v6zm12 0h-5v-6h5z");
}

</style>
