<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwjoc7-4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-drive-file-move" /></template>
<style>
.iwjoc7-4n {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l1.41 1.41l.59.59H20zm-7.84-6H8v2h4.16l-1.59 1.59L11.99 17L16 13.01L11.99 9l-1.41 1.41z");
}

</style>
