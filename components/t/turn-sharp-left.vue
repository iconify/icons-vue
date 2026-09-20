<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9otaacuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-sharp-left" /></template>
<style>
.q9otaacuk {
  fill: currentColor;
  d: path("M16 21v-6H8q-.825 0-1.412-.587T6 13V6.8L4.4 8.4L3 7l4-4l4 4l-1.4 1.4L8 6.8V13h8q.825 0 1.413.588T18 15v6z");
}

</style>
