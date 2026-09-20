<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5jiw_b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-camera-back-outline" /></template>
<style>
.x5jiw_b7f {
  fill: currentColor;
  d: path("M6 17h12l-3.75-5l-3 4L9 13zm-2 4q-.825 0-1.412-.587T2 19V7q0-.825.588-1.412T4 5h3.15L9 3h6l1.85 2H20q.825 0 1.413.588T22 7v12q0 .825-.587 1.413T20 21zm0-2h16V7h-4.05l-1.825-2h-4.25L8.05 7H4zm8-6");
}

</style>
