<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulro6bpky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-view-outline" /></template>
<style>
.ulro6bpky {
  fill: currentColor;
  d: path("M8 22q-.825 0-1.412-.587T6 20V8q0-.825.588-1.412T8 6h12q.825 0 1.413.588T22 8v12q0 .825-.587 1.413T20 22zm0-2h5v-3H8zm7 0h5v-3h-5zM2 18V4q0-.825.588-1.412T4 2h14v2H4v14zm6-3h5v-3H8zm7 0h5v-3h-5zm-7-5h12V8H8z");
}

</style>
