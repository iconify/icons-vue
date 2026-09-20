<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmjnejbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-24-filled" /></template>
<style>
.dmjnejbzd {
  fill: currentColor;
  d: path("M19.75 4A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20H4.25A2.25 2.25 0 0 1 2 17.75V6.25A2.25 2.25 0 0 1 4.25 4zM18 12v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12H3.5v5.75c0 .414.336.75.75.75h15.5a.75.75 0 0 0 .75-.75V12zM5.5 7a1 1 0 1 0 0 2a1 1 0 0 0 0-2m4 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m5.25 0a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5z");
}

</style>
