<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5gz4k18w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-landscape-outline" /></template>
<style>
.e5gz4k18w {
  fill: currentColor;
  d: path("M13 16h5V8h-5zm-7 0h5V8H6zm-2 4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zM20 6H4v12h16zM4 6v12z");
}

</style>
