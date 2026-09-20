<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl3o4ac_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vignette-rounded" /></template>
<style>
.bl3o4ac_s {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm12.225-5.187Q18 13.625 18 12t-1.775-2.812T12 8T7.775 9.188T6 12t1.775 2.813T12 16t4.225-1.187");
}

</style>
