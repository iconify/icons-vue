<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uamsnub5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tooltip-2-outline" /></template>
<style>
.uamsnub5f {
  fill: currentColor;
  d: path("M6 14h8v-2H6zm0-3h12V9H6zm0-3h12V6H6zm6 14l-2.675-4H4q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18h-5.325zm0-3.6l1.6-2.4H20V4H4v12h6.4zm0-8.4");
}

</style>
