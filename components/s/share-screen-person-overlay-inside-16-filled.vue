<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rt_74xoja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-person-overlay-inside-16-filled" /></template>
<style>
.rt_74xoja {
  fill: currentColor;
  d: path("M1 5.5A2.5 2.5 0 0 1 3.5 3h9A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5zM4 5a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm9 3.75a.75.75 0 0 0-.75-.75h-2.5a.75.75 0 0 0-.75.75v.5c0 .966.783 1.75 1.75 1.75h.498A1.75 1.75 0 0 0 13 9.252zM11 7a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
