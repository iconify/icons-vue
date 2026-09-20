<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgs2brbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-24-filled" /></template>
<style>
.cgs2brbjd {
  fill: currentColor;
  d: path("M22 12c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2s10 4.477 10 10m-7.5-4.312c0-1.097-1.43-1.518-2.024-.596l-4.157 6.443A.95.95 0 0 0 9.117 15H13v1.25a.75.75 0 0 0 1.5 0V15h.75a.75.75 0 0 0 0-1.5h-.75zM13 9.046V13.5h-2.874z");
}

</style>
