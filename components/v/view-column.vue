<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou8molblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-column" /></template>
<style>
.ou8molblz {
  fill: currentColor;
  d: path("M5 19q-.825 0-1.412-.587T3 17V7q0-.825.588-1.412T5 5h1.325q.825 0 1.413.588T8.325 7v10q0 .825-.587 1.413T6.325 19zm6.325 0q-.825 0-1.412-.587T9.325 17V7q0-.825.588-1.412T11.325 5h1.325q.825 0 1.413.588T14.65 7v10q0 .825-.587 1.413T12.65 19zm6.325 0q-.825 0-1.412-.587T15.65 17V7q0-.825.588-1.412T17.65 5h1.325q.825 0 1.413.588T20.975 7v10q0 .825-.587 1.413T18.975 19z");
}

</style>
