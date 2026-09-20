<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="h_omo0o2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-in-28-regular" /></template>
<style>
.h_omo0o2n {
  fill: currentColor;
  d: path("M11.5 2a9.5 9.5 0 0 1 9.5 9.5a9.46 9.46 0 0 1-2.275 6.164l6.055 6.056a.75.75 0 1 1-1.06 1.06l-6.056-6.055A9.46 9.46 0 0 1 11.5 21a9.5 9.5 0 0 1 0-19m0 1.5a8 8 0 1 0 0 16a8 8 0 0 0 0-16m0 3.5a.75.75 0 0 1 .75.75v3h3a.75.75 0 0 1 0 1.5h-3v3a.75.75 0 0 1-1.5 0v-3h-3a.75.75 0 0 1 0-1.5h3v-3A.75.75 0 0 1 11.5 7");
}

</style>
