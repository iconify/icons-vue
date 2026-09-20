<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr_10zbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:modeling" /></template>
<style>
.gr_10zbzf {
  fill: currentColor;
  d: path("m18 20.5l-4-4l4-4l1.4 1.4l-1.575 1.6H22v2h-4.175l1.575 1.6zM4 20q-.825 0-1.412-.587T2 18v-3q0-.825.588-1.412T4 13h6q.825 0 1.413.588T12 15v3q0 .825-.587 1.413T10 20zm2-8.5l-1.4-1.4l1.575-1.6H2v-2h4.175L4.6 4.9L6 3.5l4 4zm8-.5q-.825 0-1.412-.587T12 9V6q0-.825.588-1.412T14 4h6q.825 0 1.413.588T22 6v3q0 .825-.587 1.413T20 11z");
}

</style>
