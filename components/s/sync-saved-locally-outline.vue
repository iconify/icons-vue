<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uawpb8b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-saved-locally-outline" /></template>
<style>
.uawpb8b-j {
  fill: currentColor;
  d: path("M10.925 14.05L16.6 8.4l-1.425-1.425l-4.25 4.25L8.8 9.1l-1.4 1.4zM1 21v-2h22v2zm3-3q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18zm0-2h16V5H4zm0 0V5z");
}

</style>
