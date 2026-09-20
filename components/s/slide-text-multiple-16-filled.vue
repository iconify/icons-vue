<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mskkj6byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-multiple-16-filled" /></template>
<style>
.mskkj6byi {
  fill: currentColor;
  d: path("M1.5 4.5A2.5 2.5 0 0 1 4 2h6.5A2.5 2.5 0 0 1 13 4.5v5a2.5 2.5 0 0 1-2.5 2.5H4a2.5 2.5 0 0 1-2.5-2.5zm3-.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm0 2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM4 8.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1h-3a.5.5 0 0 0-.5.5m6.5 4.5A3.5 3.5 0 0 0 14 9.5V3.671c.625.773 1 1.757 1 2.829v3a4.5 4.5 0 0 1-4.5 4.5h-4a4.48 4.48 0 0 1-2.829-1z");
}

</style>
