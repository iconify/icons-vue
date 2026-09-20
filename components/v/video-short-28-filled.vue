<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="coegjzc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-28-filled" /></template>
<style>
.coegjzc6x {
  fill: currentColor;
  d: path("M20.25 2A3.75 3.75 0 0 1 24 5.75v16.5A3.75 3.75 0 0 1 20.25 26H7.75A3.75 3.75 0 0 1 4 22.25V5.75A3.75 3.75 0 0 1 7.75 2zm-6.955 8.23A1.5 1.5 0 0 0 11 11.5v4.998a1.5 1.5 0 0 0 2.295 1.273l4-2.5a1.5 1.5 0 0 0 0-2.545z");
}

</style>
