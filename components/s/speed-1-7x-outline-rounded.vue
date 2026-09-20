<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lztztccej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-7x-outline-rounded" /></template>
<style>
.lztztccej {
  fill: currentColor;
  d: path("M3.288 16.713Q3 16.425 3 16V9H2q-.425 0-.712-.288T1 8t.288-.712T2 7h2q.425 0 .713.288T5 8v8q0 .425-.288.713T4 17t-.712-.288M19 13.676l-1.75 2.9q-.125.2-.312.313t-.413.112q-.5 0-.762-.437t.012-.863L18 12l-2.225-3.7q-.275-.425-.012-.862T16.525 7q.225 0 .413.113t.312.312l1.75 2.9l1.75-2.9q.125-.2.313-.312T21.475 7q.5 0 .763.438t-.013.862L20 12l2.225 3.7q.275.425.013.863t-.763.437q-.225 0-.413-.112t-.312-.313zM11.25 17q-.475 0-.775-.375T10.3 15.8L12 9H9q-.425 0-.712-.288T8 8t.288-.712T9 7h3.25q.725 0 1.238.538T14 8.8l-.05.45l-1.775 7.025q-.075.325-.325.525t-.6.2m-4.962-.288Q6 16.425 6 16t.288-.712T7 15t.713.288T8 16t-.288.713T7 17t-.712-.288");
}

</style>
