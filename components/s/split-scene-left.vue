<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si9po1buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-left" /></template>
<style>
.si9po1buh {
  fill: currentColor;
  d: path("M15 20V4h4q.825 0 1.413.588T21 6v12q0 .825-.587 1.413T19 20zm-4 2v-2H5q-.825 0-1.412-.587T3 18V6q0-.825.588-1.412T5 4h6V2h2v20z");
}

</style>
