<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5aqd_bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sad-tab" /></template>
<style>
.r5aqd_bco {
  fill: currentColor;
  d: path("M7.5 16.5H9V15h6v1.5h1.5V15H15v-1.5H9V15H7.5v1.5ZM8 12h1.5V9.5H8V12Zm6.5 0H16V9.5h-1.5V12ZM4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.588 1.413T20 20H4Z");
}

</style>
