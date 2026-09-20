<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1a3fb5lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-play-pause-20-filled" /></template>
<style>
.v1a3fb5lo {
  fill: currentColor;
  d: path("M11.5 5A1.5 1.5 0 0 0 10 6.5v7a1.5 1.5 0 0 0 1.5 1.5h1a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 12.5 5zm5 0A1.5 1.5 0 0 0 15 6.5v7a1.5 1.5 0 0 0 1.5 1.5h1a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 17.5 5zm-12.574.45A1.25 1.25 0 0 0 2 6.503V13.5a1.25 1.25 0 0 0 1.916 1.057l5.496-3.461a1.25 1.25 0 0 0 .01-2.11z");
}

</style>
