<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzhm1dwvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:u-turn-left-outline-rounded" /></template>
<style>
.pzhm1dwvu {
  fill: currentColor;
  d: path("M6.625 16.513Q6.45 16.45 6.3 16.3l-2.6-2.6q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l.9.9V9q0-2.5 1.75-4.25T12 3t4.25 1.75T18 9v11q0 .425-.288.713T17 21t-.712-.288T16 20V9q0-1.65-1.175-2.825T12 5T9.175 6.175T8 9v4.2l.9-.9q.275-.275.7-.275t.7.275t.275.7t-.275.7l-2.6 2.6q-.15.15-.325.213T7 16.575t-.375-.062");
}

</style>
