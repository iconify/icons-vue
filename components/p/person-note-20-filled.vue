<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l0tz36b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-note-20-filled" /></template>
<style>
.l0tz36b-i {
  fill: currentColor;
  d: path("M10 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 3 13c0 1.691.833 2.966 2.135 3.797c1.086.692 2.493 1.075 4.026 1.176A3 3 0 0 1 9 17v-4c0-.768.289-1.47.764-2zM10 13a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2zm6.5 3h-4a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1m-4-3a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1z");
}

</style>
