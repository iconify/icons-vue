<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7ri2zq5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-content-20-filled" /></template>
<style>
.n7ri2zq5b {
  fill: currentColor;
  d: path("M15.756 4.013A2.5 2.5 0 0 1 18 6.5v7a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 2 13.5v-7A2.5 2.5 0 0 1 4.5 4h11zM6 7a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1zm5.5 5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm0-2.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm0-2.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
