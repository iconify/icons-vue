<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iw14emb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-48-regular" /></template>
<style>
.iw14emb_p {
  fill: currentColor;
  d: path("M24 6c11.046 0 20 8.954 20 20c0 5.125-3.086 9.527-7.5 11.456V38.5a5 5 0 0 0 5 5h1.25a1.25 1.25 0 1 1 0 2.5H41.5a7.5 7.5 0 0 1-7.5-7.5v-.251c-.808.164-1.644.251-2.5.251H29a7.5 7.5 0 1 1 7.5-7.5v3.658a9.99 9.99 0 0 0 5-8.658c0-9.665-7.835-17.5-17.5-17.5S6.5 16.335 6.5 26v1a6.5 6.5 0 0 0 6.5 6.5h3.75a1.25 1.25 0 1 1 0 2.5H13a9 9 0 0 1-9-9v-1C4 14.954 12.954 6 24 6m5 20a5 5 0 0 0 0 10h2.5c.863 0 1.7-.11 2.5-.315V31a5 5 0 0 0-5-5");
}

</style>
