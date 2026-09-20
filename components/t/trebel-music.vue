<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3xptpbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trebel-music" /></template>
<style>
.e3xptpbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.546 32.84V5.5h-8.078v29.544a7.457 7.457 0 0 0 7.457 7.456h5.705v-7.456h-2.88a2.203 2.203 0 0 1-2.204-2.203m11.597-14.68l-8.05-4.647v9.295zM14.91 13.514v9.295m-5.053-9.295v9.295");
}

</style>
