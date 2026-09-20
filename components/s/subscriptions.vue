<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dt7ihos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subscriptions" /></template>
<style>
.e3dt7ihos {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V10q0-.825.588-1.412T4 8h16q.825 0 1.413.588T22 10v10q0 .825-.587 1.413T20 22zm6-3l6-4l-6-4zM4 7V5h16v2zm3-3V2h10v2z");
}

</style>
