<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjs0_md2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-emoji-objects" /></template>
<style>
.kjs0_md2b {
  fill: currentColor;
  d: path("M12 3c-.42 0-.85.04-1.28.11c-2.81.5-5.08 2.75-5.6 5.55c-.48 2.61.48 5.01 2.22 6.56c.43.38.66.91.66 1.47V21h2.28a1.98 1.98 0 0 0 3.44 0H16v-4.31c0-.55.22-1.09.64-1.46A6.96 6.96 0 0 0 19 10c0-3.87-3.13-7-7-7m2 16h-4v-1h4zm0-2h-4v-1h4zm-1.5-5.59V14h-1v-2.59L9.67 9.59l.71-.71L12 10.5l1.62-1.62l.71.71z");
}

</style>
