<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogfqortst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slab-serif" /></template>
<style>
.ogfqortst {
  fill: currentColor;
  d: path("M5.75 18h5.15v-1.75H8.725l.775-2h4.85l.75 2h-2.125V18h5.275v-1.75h-1L13.2 6h-2.375L6.75 16.25h-1zm4.375-5.375l1.7-4.425H12l1.7 4.425zM4 22q-.825 0-1.412-.587T2 20V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v16q0 .825-.587 1.413T20 22z");
}

</style>
