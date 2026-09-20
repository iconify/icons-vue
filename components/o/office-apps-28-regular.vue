<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="osvupob-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:office-apps-28-regular" /></template>
<style>
.osvupob-f {
  fill: currentColor;
  d: path("M5.5 20.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4M5.5 12a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m-17-8.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
