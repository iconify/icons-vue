<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whemk9bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-5-outline" /></template>
<style>
.whemk9bzd {
  fill: currentColor;
  d: path("M7 17V9H5V7h4v10zm3 0v-2h2v2zm3 0v-2h4v-2h-4V7h6v2h-4v2h2q.825 0 1.413.588T19 13v2q0 .825-.587 1.413T17 17z");
}

</style>
