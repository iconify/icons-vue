<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1i9hsh9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-edit" /></template>
<style>
.t1i9hsh9j {
  fill: currentColor;
  d: path("M3 14V9h8v5zm0-7V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v2zm2 14q-.825 0-1.412-.587T3 19v-3h8v5zm8-7V9h8v2.3q-.95-.425-2.025-.25t-1.875.975L15.125 14zm0 8v-3.075l5.525-5.5q.225-.225.5-.325t.55-.1q.3 0 .575.113t.5.337l.925.925q.2.225.313.5t.112.55t-.1.563t-.325.512l-5.5 5.5zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
