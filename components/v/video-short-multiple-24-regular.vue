<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2572zhap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-24-regular" /></template>
<style>
.v2572zhap {
  fill: currentColor;
  d: path("M18.493 5.007a3.25 3.25 0 0 1 1.508 2.743v8.5a5.75 5.75 0 0 1-5.75 5.75h-4.5a3.25 3.25 0 0 1-2.743-1.508q.12.008.243.008h7a4.25 4.25 0 0 0 4.25-4.25v-11q0-.123-.008-.243M14.25 2a3.25 3.25 0 0 1 3.25 3.25v11a3.25 3.25 0 0 1-3.25 3.25h-7A3.25 3.25 0 0 1 4 16.25v-11A3.25 3.25 0 0 1 7.25 2zm-7 1.5A1.75 1.75 0 0 0 5.5 5.25v11c0 .966.784 1.75 1.75 1.75h7A1.75 1.75 0 0 0 16 16.25v-11a1.75 1.75 0 0 0-1.75-1.75zM8 8.754a1.25 1.25 0 0 1 1.904-1.066l3.251 1.997a1.25 1.25 0 0 1 0 2.13l-3.25 1.997A1.25 1.25 0 0 1 8 12.746z");
}

</style>
