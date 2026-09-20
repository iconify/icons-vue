<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4dxubbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-sim" /></template>
<style>
.h4dxubbrl {
  fill: currentColor;
  d: path("M20 17.175L7.4 4.6L10 2h8q.825 0 1.413.588T20 4zm.5 6.125L15.2 18l1.425-1.4L20 19.975V20q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V8l.6-.6L.7 3.5l1.425-1.4L21.9 21.875z");
}

</style>
