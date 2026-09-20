<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpzlguqaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-displays-outline" /></template>
<style>
.rpzlguqaz {
  fill: currentColor;
  d: path("M2 16V4q0-.825.588-1.412T4 2h14v2H4v12zm9 6v-2H8q-.825 0-1.412-.587T6 18V8q0-.825.588-1.412T8 6h13q.825 0 1.413.588T23 8v10q0 .825-.587 1.413T21 20h-3v2zm-3-4h13V8H8zm6.5-5");
}

</style>
