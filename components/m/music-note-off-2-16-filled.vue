<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rzuvx6vwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-off-2-16-filled" /></template>
<style>
.rzuvx6vwa {
  fill: currentColor;
  d: path("m12.553 13.26l1.593 1.594a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708L5 5.707v5.56A2 2 0 1 0 6 13V7.352l.475-.17l3.265 3.265a2 2 0 1 0 2.813 2.813M12 5.21v4.669l1 1V1.926a.8.8 0 0 0-1.07-.754L5.568 3.445L8.56 6.438z");
}

</style>
