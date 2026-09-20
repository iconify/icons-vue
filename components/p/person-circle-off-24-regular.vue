<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqq7cv97c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-24-regular" /></template>
<style>
.zqq7cv97c {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-2.201-2.2A9.96 9.96 0 0 1 12 22C6.477 22 2 17.523 2 12a9.96 9.96 0 0 1 2.419-6.52l-2.2-2.2a.75.75 0 0 1 0-1.06m3.262 4.323a8.5 8.5 0 0 0 11.973 11.973l-1.78-1.78C14.82 17.491 13.572 18 12 18c-3.14 0-5-2.029-5-4v-.5A1.5 1.5 0 0 1 8.5 12h2.44zM12 2c5.523 0 10 4.477 10 10a9.95 9.95 0 0 1-1.52 5.298l-1.094-1.094a8.5 8.5 0 0 0-11.59-11.59L6.7 3.52A9.95 9.95 0 0 1 12 2m3.5 10a1.5 1.5 0 0 1 1.5 1.5v.318L15.182 12zM12 5.5a2.75 2.75 0 0 1 2.75 2.75c0 .905-.44 1.704-1.113 2.205L9.794 6.612A2.74 2.74 0 0 1 12 5.5");
}

</style>
