<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwzg84uyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-24-filled" /></template>
<style>
.bwzg84uyn {
  fill: currentColor;
  d: path("M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2m-1 6.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 1.5 0m6 0v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 1.5 0m-3 1.5v3.5a.75.75 0 0 1-1.5 0v-3.5a.75.75 0 0 1 1.5 0m-6 .5v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0");
}

</style>
