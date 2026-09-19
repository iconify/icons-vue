<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3g7lubes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-view-module" /></template>
<style>
.g3g7lubes {
  fill: currentColor;
  d: path("M14.67 6v4.5c0 .55-.45 1-1 1h-3.33c-.55 0-1-.45-1-1V6c0-.55.45-1 1-1h3.33c.55 0 1 .45 1 1m2 5.5H20c.55 0 1-.45 1-1V6c0-.55-.45-1-1-1h-3.33c-.55 0-1 .45-1 1v4.5c0 .55.44 1 1 1m-2 6.5v-4.5c0-.55-.45-1-1-1h-3.33c-.55 0-1 .45-1 1V18c0 .55.45 1 1 1h3.33c.55 0 1-.45 1-1m1-4.5V18c0 .55.45 1 1 1H20c.55 0 1-.45 1-1v-4.5c0-.55-.45-1-1-1h-3.33c-.56 0-1 .45-1 1m-8.34-1H4c-.55 0-1 .45-1 1V18c0 .55.45 1 1 1h3.33c.55 0 1-.45 1-1v-4.5c0-.55-.44-1-1-1m1-2V6c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v4.5c0 .55.45 1 1 1h3.33c.56 0 1-.45 1-1");
}

</style>
