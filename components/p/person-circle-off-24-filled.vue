<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="balubbbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-24-filled" /></template>
<style>
.balubbbaq {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-2.201-2.2A9.96 9.96 0 0 1 12 22C6.477 22 2 17.523 2 12a9.96 9.96 0 0 1 2.419-6.52l-2.2-2.2a.75.75 0 0 1 0-1.06M8.5 12A1.5 1.5 0 0 0 7 13.5v.5c0 1.971 1.86 4 5 4c1.57 0 2.819-.51 3.676-1.264L10.94 12zM12 2c5.523 0 10 4.477 10 10a9.95 9.95 0 0 1-1.52 5.298L17 13.818V13.5a1.5 1.5 0 0 0-1.5-1.5h-.318l-1.545-1.545A2.74 2.74 0 0 0 14.75 8.25a2.75 2.75 0 0 0-4.956-1.638L6.701 3.52A9.95 9.95 0 0 1 12 2");
}

</style>
