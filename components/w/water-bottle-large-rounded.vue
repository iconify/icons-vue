<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8uay34f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-bottle-large-rounded" /></template>
<style>
.zb8uay34f {
  fill: currentColor;
  d: path("M7 22q-.825 0-1.412-.587T5 20v-2q0-.825.588-1.412T7 16v-5q-.825 0-1.412-.587T5 9V7q0-.825.588-1.412T7 5h3V4q-.425 0-.712-.288T9 3t.288-.712T10 2h4q.425 0 .713.288T15 3t-.288.713T14 4v1h3q.825 0 1.413.588T19 7v2q0 .825-.587 1.413T17 11v5q.825 0 1.413.588T19 18v2q0 .825-.587 1.413T17 22z");
}

</style>
