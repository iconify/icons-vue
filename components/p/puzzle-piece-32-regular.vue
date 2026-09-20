<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixb6f6ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-piece-32-regular" /></template>
<style>
.ixb6f6ban {
  fill: currentColor;
  d: path("M17 4a2 2 0 0 0-2 2v2H9.75a.75.75 0 0 0-.75.75V14H7a2 2 0 1 0 0 4h2v5.25c0 .414.336.75.75.75H15v2a2 2 0 1 0 4 0v-2h5.25a.75.75 0 0 0 .75-.75V20h-1a4 4 0 0 1 0-8h1V8.75a.75.75 0 0 0-.75-.75H19V6a2 2 0 0 0-2-2m-4 2a4 4 0 0 1 8 0h3.25A2.75 2.75 0 0 1 27 8.75V14h-3a2 2 0 1 0 0 4h3v5.25A2.75 2.75 0 0 1 24.25 26H21a4 4 0 0 1-8 0H9.75A2.75 2.75 0 0 1 7 23.25V20a4 4 0 0 1 0-8V8.75A2.75 2.75 0 0 1 9.75 6z");
}

</style>
