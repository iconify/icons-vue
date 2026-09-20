<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vzhdc8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skillet-cooktop" /></template>
<style>
.x9vzhdc8i {
  fill: currentColor;
  d: path("M6 15q-1.25 0-2.125-.875T3 12V8h13.025q.125-.825.675-1.475t1.35-.925l4.625-1.55l.625 1.9l-4.625 1.55q-.3.1-.488.363T18 8.45V12q0 1.25-.875 2.125T15 15zm3 6v-3H2v-2h7q.825 0 1.413.588T11 18v3zm4 0v-3q0-.825.588-1.412T15 16h7v2h-7v3z");
}

</style>
