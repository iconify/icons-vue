<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6ugpb7qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-money-24-filled" /></template>
<style>
.p6ugpb7qc {
  fill: currentColor;
  d: path("M8 11a4 4 0 1 0 0-8a4 4 0 0 0 0 8m9 0a3 3 0 1 0 0-6a3 3 0 0 0 0 6M4.25 13A2.25 2.25 0 0 0 2 15.25v.25S2 20 8 20c1.238 0 2.22-.192 3-.495V15.5c0-1.064.665-1.972 1.601-2.334A2.2 2.2 0 0 0 11.75 13zM12 15.5a1.5 1.5 0 0 1 1.5-1.5h8a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-8a1.5 1.5 0 0 1-1.5-1.5zm1 .5v1a2 2 0 0 0 2-2h-1a1 1 0 0 1-1 1m9 1v-1a1 1 0 0 1-1-1h-1a2 2 0 0 0 2 2m-2 3h1a1 1 0 0 1 1-1v-1a2 2 0 0 0-2 2m-7-2v1a1 1 0 0 1 1 1h1a2 2 0 0 0-2-2m4.5 1.25a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

</style>
