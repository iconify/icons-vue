<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq0tog9pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-select-range-24-filled" /></template>
<style>
.lq0tog9pq {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM10 19.5h4v-4h-4zm5.5 0h2.25a1.75 1.75 0 0 0 1.75-1.75V15.5h-4zm-11-1.75c0 .966.784 1.75 1.75 1.75H8.5v-4h-4zm11-3.75h4v-4h-4zm0-5.5h4V6.25a1.75 1.75 0 0 0-1.75-1.75H15.5z");
}

</style>
