<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfoj5wb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-16-filled" /></template>
<style>
.cfoj5wb3h {
  fill: currentColor;
  d: path("M9.5 1a.5.5 0 0 1 0 1h-1v12h1a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1h1V2h-1a.5.5 0 0 1 0-1zm-3 12h-3A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3h3zm6-10A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-3V3z");
}

</style>
