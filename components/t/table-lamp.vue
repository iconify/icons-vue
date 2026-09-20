<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8mgoglqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-lamp" /></template>
<style>
.r8mgoglqd {
  fill: currentColor;
  d: path("M13 21v-2h8v2zm3-3V8q0-.425-.288-.712T15 7h-4v3q0 .425-.288.713T10 11H4q-.55 0-.85-.45t-.075-.95L5.45 4.2q.25-.55.737-.875T7.275 3H9q.825 0 1.413.588T11 5h4q1.25 0 2.125.875T18 8v10z");
}

</style>
