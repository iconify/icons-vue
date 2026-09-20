<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqu5iab4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:top-panel-open-outline" /></template>
<style>
.zqu5iab4t {
  fill: currentColor;
  d: path("m12 16.5l4-4H8zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM19 8V5H5v3zM5 10v9h14v-9zm0-2V5z");
}

</style>
