<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx2dutbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mp" /></template>
<style>
.dx2dutbak {
  fill: currentColor;
  d: path("M6 15h1.5v-4.5h1v3H10v-3h1V15h1.5v-5q0-.425-.288-.712T11.5 9H7q-.425 0-.712.288T6 10zm7.5 0H15v-1.5h2q.425 0 .713-.288T18 12.5V10q0-.425-.288-.712T17 9h-3.5zm1.5-3v-1.5h1.5V12zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
