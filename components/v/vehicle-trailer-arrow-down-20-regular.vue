<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i7ifmac9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-arrow-down-20-regular" /></template>
<style>
.i7ifmac9t {
  fill: currentColor;
  d: path("M6.5 12a.5.5 0 0 1 .5.5v4.793l1.146-1.146a.5.5 0 1 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.707L6 17.293V12.5a.5.5 0 0 1 .5-.5m6.654-8.996A3 3 0 0 1 16 6v8h2v-1.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V15H8v-1h7V6a2 2 0 0 0-1.796-1.99L13 4h-3a8 8 0 0 0-8 8a2 2 0 0 0 2 2h1v1H4a3 3 0 0 1-3-3a9 9 0 0 1 9-9h3zM12 6a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1zm-3 4h3V7H9z");
}

</style>
