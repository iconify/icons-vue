<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2pb_ubvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:restore-page-outline" /></template>
<style>
.m2pb_ubvl {
  fill: currentColor;
  d: path("M12 17.75q1.95 0 3.35-1.4t1.4-3.35t-1.4-3.35T12 8.25q-.95 0-1.775.35t-1.475.95V8h-1.5v4.25h4.25v-1.5H9.7q.425-.45 1.025-.725T12 9.75q1.35 0 2.3.95t.95 2.3t-.95 2.3t-2.3.95q-1.1 0-1.925-.638T8.9 14H7.35q.35 1.625 1.638 2.688T12 17.75M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm0-2h12V8.85L13.15 4H6zm0 0V4z");
}

</style>
