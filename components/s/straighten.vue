<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utvu1pbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:straighten" /></template>
<style>
.utvu1pbcz {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V8q0-.825.588-1.412T4 6h3v6h2V6h2v6h2V6h2v6h2V6h3q.825 0 1.413.588T22 8v8q0 .825-.587 1.413T20 18z");
}

</style>
