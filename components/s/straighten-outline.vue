<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqhabjbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:straighten-outline" /></template>
<style>
.sqhabjbgt {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V8q0-.825.588-1.412T4 6h16q.825 0 1.413.588T22 8v8q0 .825-.587 1.413T20 18zm0-2h16V8h-3v4h-2V8h-2v4h-2V8H9v4H7V8H4zm3-4h2zm4 0h2zm4 0h2zm-3 0");
}

</style>
