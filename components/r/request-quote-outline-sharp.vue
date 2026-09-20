<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oltllnuzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:request-quote-outline-sharp" /></template>
<style>
.oltllnuzx {
  fill: currentColor;
  d: path("M11.846 18.25h1v-1h2v-4h-4v-2h4v-1h-2v-1h-1v1h-2v4h4v2h-4v1h2zM5 21V3h9.73L19 7.27V21zm1-1h12V7.77h-3.77V4H6zM6 4v3.77zv16z");
}

</style>
