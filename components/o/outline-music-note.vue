<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbio7abts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-music-note" /></template>
<style>
.rbio7abts {
  fill: currentColor;
  d: path("m12 3l.01 10.55c-.59-.34-1.27-.55-2-.55a4.001 4.001 0 1 0 0 8c2.22 0 3.99-1.79 3.99-4V7h4V3zm-1.99 16c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

</style>
