<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn38_hmxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:man-2-outline" /></template>
<style>
.zn38_hmxk {
  fill: currentColor;
  d: path("M10.5 22v-7H8V9q0-.825.588-1.412T10 7h4q.825 0 1.413.588T16 9v6h-2.5v7zM12 6q-.825 0-1.412-.587T10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6");
}

</style>
