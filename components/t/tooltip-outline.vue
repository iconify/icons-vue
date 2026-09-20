<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8v_-dbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tooltip-outline" /></template>
<style>
.i8v_-dbdo {
  fill: currentColor;
  d: path("m12 22l-2.675-4H4q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18h-5.325zm0-3.6l1.6-2.4H20V4H4v12h6.4zm0-8.4");
}

</style>
