<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsh1bzb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:usb-outline" /></template>
<style>
.nsh1bzb2g {
  fill: currentColor;
  d: path("M10.588 21.413Q10 20.825 10 20q0-.525.275-.975T11 18.3V16H8q-.825 0-1.412-.587T6 14v-2.3q-.45-.225-.725-.675T5 10q0-.825.588-1.413T7 8t1.413.588T9 10q0 .575-.275 1T8 11.7V14h3V6H9l3-4l3 4h-2v8h3v-2h-1V8h4v4h-1v2q0 .825-.587 1.413T16 16h-3v2.3q.475.25.738.7T14 20q0 .825-.587 1.413T12 22t-1.412-.587");
}

</style>
