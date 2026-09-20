<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huikgislv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-speaker-24-filled" /></template>
<style>
.huikgislv {
  fill: currentColor;
  d: path("M18.63 11.176a.75.75 0 0 1 1.058.092a7.72 7.72 0 0 1 1.813 4.981a7.72 7.72 0 0 1-1.814 4.982a.75.75 0 0 1-1.148-.965a6.22 6.22 0 0 0 1.462-4.017c0-1.53-.55-2.93-1.462-4.017a.75.75 0 0 1 .092-1.056m-5.918 1.045a.75.75 0 0 1 1.281.529v3.403a.8.8 0 0 1 0 .19v3.408a.75.75 0 0 1-1.281.53L10.43 18H8.75a.75.75 0 0 1-.75-.75V17H2.75a.75.75 0 0 1 0-1.5H8v-.25a.75.75 0 0 1 .75-.75h1.685zm3.129.536a.75.75 0 0 1 1.058-.065a4.74 4.74 0 0 1 1.602 3.557c0 1.416-.62 2.688-1.602 3.557a.75.75 0 0 1-.994-1.123a3.24 3.24 0 0 0 1.096-2.434a3.24 3.24 0 0 0-1.096-2.434a.75.75 0 0 1-.064-1.058M8.75 3a3.25 3.25 0 0 1 3.162 2.5h9.338a.75.75 0 0 1 0 1.5h-9.338a3.25 3.25 0 0 1-6.324 0H2.75a.75.75 0 0 1 0-1.5h2.838A3.25 3.25 0 0 1 8.75 3");
}

</style>
