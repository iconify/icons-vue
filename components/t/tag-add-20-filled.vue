<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c2emtsb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-add-20-filled" /></template>
<style>
.c2emtsb5a {
  fill: currentColor;
  d: path("M18.006 4.033a2 2 0 0 0-1.987-1.997l-4.89-.032a2 2 0 0 0-1.426.584L3.02 9.252a2 2 0 0 0-.002 2.83l4.949 4.95a2 2 0 0 0 1.95.512a5.5 5.5 0 0 1 7.796-7.507a2 2 0 0 0 .299-1.054zM13.999 7a1 1 0 1 1 0-2a1 1 0 0 1 0 2M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15z");
}

</style>
