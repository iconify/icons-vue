<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw0dz5cnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-lock-outline" /></template>
<style>
.rw0dz5cnl {
  fill: currentColor;
  d: path("M4 20v-2h2.725q-1.275-1.1-2-2.65T4 12q0-2.8 1.7-4.937T10 4.25v2.1q-1.75.625-2.875 2.163T6 12q0 1.35.538 2.488T8 16.45V14h2v6zm14-8q0-1.275-.513-2.387T16 7.55V10h-2V4h6v2h-2.725q1.475 1.325 2.088 2.838T20 12zm-2 10q-.425 0-.712-.288T15 21v-3q0-.425.288-.712T16 17v-1q0-.825.588-1.412T18 14t1.413.588T20 16v1q.425 0 .713.288T21 18v3q0 .425-.288.713T20 22zm1-5h2v-1q0-.425-.288-.712T18 15t-.712.288T17 16z");
}

</style>
