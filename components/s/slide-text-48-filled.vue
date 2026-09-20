<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sf3moobku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-48-filled" /></template>
<style>
.sf3moobku {
  fill: currentColor;
  d: path("M4 12.75A4.75 4.75 0 0 1 8.75 8h30.5A4.75 4.75 0 0 1 44 12.75v22.5A4.75 4.75 0 0 1 39.25 40H8.75A4.75 4.75 0 0 1 4 35.25zm9.25 9.75a1.25 1.25 0 1 0 0 2.5h17.5a1.25 1.25 0 1 0 0-2.5zM12 30.25c0 .69.56 1.25 1.25 1.25h13.5a1.25 1.25 0 1 0 0-2.5h-13.5c-.69 0-1.25.56-1.25 1.25M13.25 16a1.25 1.25 0 1 0 0 2.5h9.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
