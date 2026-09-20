<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er3i_e_qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-lock-portrait-outline-sharp" /></template>
<style>
.er3i_e_qy {
  fill: currentColor;
  d: path("M9 16v-5h1v-1q0-.825.588-1.412T12 8t1.413.588T14 10v1h1v5zm2-5h2v-1q0-.425-.288-.712T12 9t-.712.288T11 10zM5 23V1h14v22zm2-3v1h10v-1zm0-2h10V6H7zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
