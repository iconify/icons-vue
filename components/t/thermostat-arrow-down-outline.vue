<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5keapbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thermostat-arrow-down-outline" /></template>
<style>
.o5keapbjo {
  fill: currentColor;
  d: path("M4.463 19.538Q3 18.075 3 16q0-1.2.525-2.238T5 12V6q0-1.25.875-2.125T8 3t2.125.875T11 6v6q.95.725 1.475 1.763T13 16q0 2.075-1.463 3.538T8 21t-3.537-1.463M5 16h6q0-.725-.312-1.35T9.8 13.6L9 13V6q0-.425-.288-.712T8 5t-.712.288T7 6v7l-.8.6q-.575.425-.888 1.05T5 16m14.5 4L16 16.5l1.425-1.4l1.075 1.075V4h2v12.2l1.1-1.1l1.4 1.4z");
}

</style>
