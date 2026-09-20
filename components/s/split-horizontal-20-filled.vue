<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ol4q0z94u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-20-filled" /></template>
<style>
.ol4q0z94u {
  fill: currentColor;
  d: path("M17.5 10a.5.5 0 0 0 0-1h-15a.5.5 0 0 0 0 1zM14 2a2 2 0 0 1 2 2v4H4V4a2 2 0 0 1 2-2zM4 11v4a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-4z");
}

</style>
