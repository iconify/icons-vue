<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fddwn5r7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-email-outline" /></template>
<style>
.fddwn5r7a {
  fill: currentColor;
  d: path("M7 17q-.825 0-1.412-.587T5 15V5q0-.825.588-1.412T7 3h14q.825 0 1.413.588T23 5v10q0 .825-.587 1.413T21 17zm7-4.7L7 7.425V15h14V7.425zm0-2.45L21 5H7zM3 21q-.825 0-1.412-.587T1 19V6.5h2V19h16.5v2zM21 7.35V5H7v2.35V5h14z");
}

</style>
