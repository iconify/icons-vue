<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoem69bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-current-landscape-outline" /></template>
<style>
.zoem69bvd {
  fill: currentColor;
  d: path("M3 19q-.825 0-1.412-.587T1 17V7q0-.825.588-1.412T3 5h18q.825 0 1.413.588T23 7v10q0 .825-.587 1.413T21 19zm1-2V7H3v10zm2 0h12V7H6zm14 0h1V7h-1zM4 7H3zm16 0h1z");
}

</style>
