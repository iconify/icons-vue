<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owfyyhbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-2x-outline" /></template>
<style>
.owfyyhbjs {
  fill: currentColor;
  d: path("M5 17v-4q0-.825.588-1.412T7 11h2V9H5V7h4q.825 0 1.413.588T11 9v2q0 .825-.587 1.413T9 13H7v2h4v2zm7 0l3-5l-3-5h2l2 3.325L18 7h2l-3 5l3 5h-2l-2-3.325L14 17z");
}

</style>
