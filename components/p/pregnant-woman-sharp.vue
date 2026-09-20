<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as-5r8eit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pregnant-woman-sharp" /></template>
<style>
.as-5r8eit {
  fill: currentColor;
  d: path("M10 22v-5H8v-7q0-1.25.875-2.125T11 7t2.125.875T14 10q.9.375 1.45 1.2T16 13v4h-3v5zM9.587 5.412Q9 4.825 9 4t.588-1.412T11 2t1.413.588T13 4t-.587 1.413T11 6t-1.412-.587");
}

</style>
