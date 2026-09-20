<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b6zjcsgaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-microphone-20-regular" /></template>
<style>
.b6zjcsgaa {
  fill: currentColor;
  d: path("M18.5 13.5a.5.5 0 0 1 .5.5a4 4 0 0 1-3.5 3.968v.532a.5.5 0 0 1-1 0v-.532A4 4 0 0 1 11 14a.5.5 0 0 1 1 0a3 3 0 1 0 6 0a.5.5 0 0 1 .5-.5m-3-9.5A2.5 2.5 0 0 1 18 6.5V12a3 3 0 0 0-1-2.232V6.5A1.5 1.5 0 0 0 15.5 5h-11A1.5 1.5 0 0 0 3 6.5v7A1.5 1.5 0 0 0 4.5 15h5.6q.107.523.316 1H4.5A2.5 2.5 0 0 1 2 13.5v-7A2.5 2.5 0 0 1 4.5 4zm-.5 6a2 2 0 0 1 2 2v2a2 2 0 1 1-4 0v-2a2 2 0 0 1 2-2m-5 2a.5.5 0 0 1 0 1H5.5a.5.5 0 0 1 0-1zm1.5-2.5a.5.5 0 0 1 0 1h-6a.5.5 0 0 1 0-1zM9.5 7a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1z");
}

</style>
