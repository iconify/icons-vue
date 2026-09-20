<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c49f9cb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-32-regular" /></template>
<style>
.c49f9cb7a {
  fill: currentColor;
  d: path("M12 10.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 5.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-1.5 7a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M14 10.5a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1m1 4.5a1 1 0 1 0 0 2h7a1 1 0 1 0 0-2zm-1 6.5a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3zM5 7.5A2.5 2.5 0 0 1 7.5 5h17A2.5 2.5 0 0 1 27 7.5v17a2.5 2.5 0 0 1-2.5 2.5h-17A2.5 2.5 0 0 1 5 24.5z");
}

</style>
