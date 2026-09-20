<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klckd3c2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-24-filled" /></template>
<style>
.klckd3c2b {
  fill: currentColor;
  d: path("M18.493 5.007a3.25 3.25 0 0 1 1.508 2.743v8.5a5.75 5.75 0 0 1-5.75 5.75h-4.5a3.25 3.25 0 0 1-2.743-1.508q.12.008.243.008h7a4.25 4.25 0 0 0 4.25-4.25v-11q0-.123-.008-.243M14.25 2a3.25 3.25 0 0 1 3.25 3.25v11a3.25 3.25 0 0 1-3.25 3.25h-7A3.25 3.25 0 0 1 4 16.25v-11A3.25 3.25 0 0 1 7.25 2zM9.904 7.688A1.25 1.25 0 0 0 8 8.754v3.992a1.25 1.25 0 0 0 1.904 1.066l3.251-1.997a1.25 1.25 0 0 0 0-2.13z");
}

</style>
