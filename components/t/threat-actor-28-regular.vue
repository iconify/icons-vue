<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c6i4rf9yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-28-regular" /></template>
<style>
.c6i4rf9yf {
  fill: currentColor;
  d: path("M14.002 2c5.05 0 9.367 3.12 11.139 7.536A2.25 2.25 0 0 1 27 11.75v1.5c0 .78-.397 1.466-1 1.87v2.904a5.976 5.976 0 0 1-10.26 4.165l-.665-.683a1.5 1.5 0 0 0-2.15 0l-.665.683A5.976 5.976 0 0 1 2 18.025V15.12c-.603-.404-1-1.09-1-1.87v-1.5a2.25 2.25 0 0 1 1.862-2.215C4.634 5.12 8.952 2 14.002 2m-8.6 14.5a3 3 0 0 0 5.197 3zm12 3a3 3 0 0 0 5.197-3zM3.25 11a.75.75 0 0 0-.75.75v1.5c0 .414.336.75.75.75h21.5a.75.75 0 0 0 .75-.75v-1.5a.75.75 0 0 0-.75-.75zm10.752-7.5c-4.188 0-7.8 2.453-9.485 6h18.97a10.5 10.5 0 0 0-9.485-6");
}

</style>
