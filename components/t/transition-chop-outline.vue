<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-tu2477a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-chop-outline" /></template>
<style>
.o-tu2477a {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-3.45l11.55-3L13.6 6H4zM6.375 18H20V6h-4.325L18 15zM4 6");
}

</style>
