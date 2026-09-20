<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gji_k6b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-android-rounded" /></template>
<style>
.gji_k6b6x {
  fill: currentColor;
  d: path("M5 23q-.825 0-1.412-.587T3 21V3q0-.825.588-1.412T5 1h14q.825 0 1.413.588T21 3v18q0 .825-.587 1.413T19 23zm0-7h14V6H5zm5.5 4h3q.2 0 .35-.15t.15-.35t-.15-.35t-.35-.15h-3q-.2 0-.35.15t-.15.35t.15.35t.35.15");
}

</style>
