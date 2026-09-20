<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrgqqkkwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-jam-outline" /></template>
<style>
.vrgqqkkwu {
  fill: currentColor;
  d: path("M6 21h12v-2h-5v-7.2l1.6 1.6L16 12l-4-4l-4 4l1.4 1.4l1.6-1.6V19H6zm-2-5q-.825 0-1.412-.587T2 14V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v9q0 .825-.587 1.413T20 16h-5v-2h5V5H4v9h5v2z");
}

</style>
