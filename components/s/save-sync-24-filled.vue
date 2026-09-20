<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on9bwibta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-sync-24-filled" /></template>
<style>
.on9bwibta {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M6.75 7.5A2.25 2.25 0 0 0 9 9.75h4.5a2.25 2.25 0 0 0 2.25-2.25V3a3.25 3.25 0 0 1 2.263.952l2.035 2.035c.61.61.952 1.436.952 2.298v3.74A6.47 6.47 0 0 0 17.5 11a6.48 6.48 0 0 0-4.435 1.75H8.25A2.25 2.25 0 0 0 6 15v6h-.25A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3h1zm5.122 6.75A6.47 6.47 0 0 0 11 17.5c0 1.29.377 2.49 1.024 3.5H7.5v-6a.75.75 0 0 1 .75-.75zM14.5 18a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-.55A3.5 3.5 0 0 0 17.5 21a3.5 3.5 0 0 0 2.675-1.243a.5.5 0 1 0-.764-.646A2.5 2.5 0 0 1 17.5 20a2.5 2.5 0 0 1-2-1h1a.5.5 0 0 0 0-1zm6-4a.5.5 0 0 0-.5.5v.55A3.5 3.5 0 0 0 17.5 14a3.5 3.5 0 0 0-2.837 1.45a.5.5 0 0 0 .81.586A2.5 2.5 0 0 1 17.5 15c.817 0 1.543.392 2 1h-1a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5m-6.25-6.5a.75.75 0 0 1-.75.75H9a.75.75 0 0 1-.75-.75V3h6z");
}

</style>
