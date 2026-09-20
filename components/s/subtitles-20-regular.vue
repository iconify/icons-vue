<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bt8hdimzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtitles-20-regular" /></template>
<style>
.bt8hdimzx {
  fill: currentColor;
  d: path("M2 6.75A2.75 2.75 0 0 1 4.75 4h10.5A2.75 2.75 0 0 1 18 6.75v6.5A2.75 2.75 0 0 1 15.25 16H4.75A2.75 2.75 0 0 1 2 13.25zM4.75 5A1.75 1.75 0 0 0 3 6.75v6.5c0 .966.784 1.75 1.75 1.75h10.5A1.75 1.75 0 0 0 17 13.25v-6.5A1.75 1.75 0 0 0 15.25 5zM4 11.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5m.5 1.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm8.5-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5M9.5 13a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1z");
}

</style>
