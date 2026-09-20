<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgsfpkbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-note-add" /></template>
<style>
.fgsfpkbsz {
  fill: currentColor;
  d: path("M9.992 18.93q-.877-.876-.877-2.122q0-1.247.882-2.124q.881-.876 2.119-.876q.575 0 1.09.204t.91.615V4.192H19v2.539h-3.884v10.077q0 1.237-.877 2.118t-2.124.882t-2.123-.877m-2.761-7.739v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
