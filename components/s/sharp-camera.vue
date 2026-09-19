<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8h7z-bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-camera" /></template>
<style>
.o8h7z-bwx {
  fill: currentColor;
  d: path("m9.4 10.5l4.77-8.26a9.98 9.98 0 0 0-8.49 2.01l3.66 6.35zM21.54 9c-.92-2.92-3.15-5.26-6-6.34L11.88 9zm.26 1h-7.49l.29.5l4.76 8.25A9.9 9.9 0 0 0 22 12c0-.69-.07-1.35-.2-2M8.54 12l-3.9-6.75A9.96 9.96 0 0 0 2.2 14h7.49zm-6.08 3c.92 2.92 3.15 5.26 6 6.34L12.12 15zm11.27 0l-3.9 6.76a9.98 9.98 0 0 0 8.49-2.01l-3.66-6.35z");
}

</style>
