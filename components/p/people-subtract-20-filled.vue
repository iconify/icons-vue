<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mx_fsoldy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-subtract-20-filled" /></template>
<style>
.mx_fsoldy {
  fill: currentColor;
  d: path("M10 5.75a3.25 3.25 0 1 1-6.5 0a3.25 3.25 0 0 1 6.5 0M14.5 9a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m-3.507 1.263A5.49 5.49 0 0 0 9 14.5q.001.593.121 1.153c-.638.215-1.418.347-2.371.347c-5.25 0-5.25-4-5.25-4a2 2 0 0 1 2-2H10a2 2 0 0 1 .993.263M14.5 19a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M12 14.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>
