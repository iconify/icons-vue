<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0oqkhbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-open-rounded" /></template>
<style>
.s0oqkhbmw {
  fill: currentColor;
  d: path("M6 21q-.825 0-1.412-.587T4 19V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v14q0 .825-.587 1.413T18 21zm1-10h4v-.5q0-.2.15-.35t.35-.15h1q.2 0 .35.15t.15.35v.5h4V6H7zm-1 8h12V5H6z");
}

</style>
