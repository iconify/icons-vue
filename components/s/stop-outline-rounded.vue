<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z16yv3bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stop-outline-rounded" /></template>
<style>
.z16yv3bha {
  fill: currentColor;
  d: path("M6 16V8q0-.825.588-1.412T8 6h8q.825 0 1.413.588T18 8v8q0 .825-.587 1.413T16 18H8q-.825 0-1.412-.587T6 16m2 0h8V8H8zm4-4");
}

</style>
