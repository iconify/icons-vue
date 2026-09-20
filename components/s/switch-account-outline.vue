<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6aacb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-account-outline" /></template>
<style>
.zx6aacb5a {
  fill: currentColor;
  d: path("M16.125 10.125Q17 9.25 17 8t-.875-2.125T14 5t-2.125.875T11 8t.875 2.125T14 11t2.125-.875M8 15.75q1.125-1.325 2.7-2.037T14 13t3.3.713T20 15.75V4H8zM8 18q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-4 4q-.825 0-1.412-.587T2 20V6h2v14h14v2zm9.288-13.288Q13 8.425 13 8t.288-.712T14 7t.713.288T15 8t-.288.713T14 9t-.712-.288M10.7 16h6.6q-.725-.5-1.575-.75T14 15t-1.725.25T10.7 16M14 9.875");
}

</style>
