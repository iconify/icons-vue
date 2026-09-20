<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtfg5zbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-open-rounded" /></template>
<style>
.jtfg5zbks {
  fill: currentColor;
  d: path("M11.5 14.8V9.2q0-.35-.3-.475t-.55.125L8.2 11.3q-.3.3-.3.7t.3.7l2.45 2.45q.25.25.55.125t.3-.475M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm9-2V5H5v14z");
}

</style>
