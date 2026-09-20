<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3hfwyb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pan-zoom-outline-rounded" /></template>
<style>
.m3hfwyb-z {
  fill: currentColor;
  d: path("M6.4 19H8q.425 0 .713.288T9 20t-.288.713T8 21H4q-.425 0-.712-.288T3 20v-4q0-.425.288-.712T4 15t.713.288T5 16v1.6l2.4-2.4q.275-.275.7-.275t.7.275t.275.7t-.275.7zM19 6.4l-2.4 2.4q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7L17.6 5H16q-.425 0-.712-.288T15 4t.288-.712T16 3h4q.425 0 .713.288T21 4v4q0 .425-.288.713T20 9t-.712-.288T19 8z");
}

</style>
