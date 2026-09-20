<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iz5mvebeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-48-filled" /></template>
<style>
.iz5mvebeg {
  fill: currentColor;
  d: path("M33.048 24.722a3 3 0 0 1 3.904 0l8 6.852A3 3 0 0 1 46 33.852V44a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-6a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v6a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2V33.853a3 3 0 0 1 1.048-2.279zm-9.3 5.334A5 5 0 0 0 22 33.852v10.08c-3.449-.227-6.62-1.055-9.08-2.552C9.942 39.567 8 36.755 8 33v-.751A4.25 4.25 0 0 1 12.25 28h13.897zM24 4c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10S18.477 4 24 4");
}

</style>
