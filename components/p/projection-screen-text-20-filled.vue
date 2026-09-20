<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w96_i3bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:projection-screen-text-20-filled" /></template>
<style>
.w96_i3bmh {
  fill: currentColor;
  d: path("M1 3.5A1.5 1.5 0 0 1 2.5 2h15a1.5 1.5 0 0 1 .5 2.915V12a3 3 0 0 1-3 3h-4.5v2h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2H5a3 3 0 0 1-3-3V4.915A1.5 1.5 0 0 1 1 3.5M7.5 7a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM6 9.5a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 0-1h-7a.5.5 0 0 0-.5.5M7.5 11a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
