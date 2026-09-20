<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlmkbjjka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-cam-stand-sharp" /></template>
<style>
.tlmkbjjka {
  fill: currentColor;
  d: path("m3.8 21l.8-9.2q.125-1.8 1.05-3.275T8 6.15V10q0 1.65 1.175 2.825T12 14q1.675 0 2.838-1.175T16 10V6.15q1.425.9 2.35 2.375T19.4 11.8l.775 9.2zm6.788-9.587Q10 10.825 10 10V6q0-.825.588-1.412T12 4t1.413.588T14 6v4q0 .825-.587 1.413T12 12t-1.412-.587");
}

</style>
