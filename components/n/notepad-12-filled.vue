<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ufr01zbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notepad-12-filled" /></template>
<style>
.ufr01zbag {
  fill: currentColor;
  d: path("M4 1.5a.5.5 0 0 1 1 0V2h2v-.5a.5.5 0 0 1 1 0V2a2 2 0 0 1 2 2v3H7.5A1.5 1.5 0 0 0 6 8.5V11H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm0 3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1h-3a.5.5 0 0 0-.5.5m0 2a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1h-1a.5.5 0 0 0-.5.5M4.5 9a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1M7 8.5a.5.5 0 0 1 .5-.5H10l-3 3z");
}

</style>
