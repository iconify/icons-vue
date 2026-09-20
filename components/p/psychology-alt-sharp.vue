<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfw3kggys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:psychology-alt-sharp" /></template>
<style>
.nfw3kggys {
  fill: currentColor;
  d: path("M6 22v-4.3q-1.425-1.3-2.212-3.037T3 11q0-3.75 2.625-6.375T12 2q3.125 0 5.538 1.838t3.137 4.787l1.6 6.375H19v5h-4v2zm6-6q.425 0 .713-.288T13 15t-.288-.712T12 14t-.712.288T11 15t.288.713T12 16m-.75-3.2h1.525q0-.625.163-1.012t.662-.938q.45-.5.875-1.012T14.9 8.5q0-1.05-.812-1.775T12.075 6q-1 0-1.812.575t-1.138 1.5l1.375.575q.175-.55.613-.888t.962-.337q.55 0 .913.3t.362.775q0 .525-.312.938t-.738.837q-.5.525-.775 1.05T11.25 12.8");
}

</style>
