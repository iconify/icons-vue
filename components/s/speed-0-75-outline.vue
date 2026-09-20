<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqwprfs6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-75-outline" /></template>
<style>
.gqwprfs6f {
  fill: currentColor;
  d: path("M5 17v-2h2v2zm9 0v-2h4v-2h-4V7h6v2h-4v2h2q.825 0 1.413.588T20 13v2q0 .825-.587 1.413T18 17zm-5 0l2-8H7V7h4.25q.725 0 1.238.538T13 8.8l-.05.45L11 17z");
}

</style>
