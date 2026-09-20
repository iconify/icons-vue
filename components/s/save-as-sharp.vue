<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7sivbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:save-as-sharp" /></template>
<style>
.lo7sivbyu {
  fill: currentColor;
  d: path("M13 23v-3.075l6.575-6.55l3.075 3.05L16.075 23zM6 10h9V6H6zm13.575 7.4l.925-.975l-.925-.925l-.95.95zM11 21H3V3h14l4 4v2.15l-6 5.975V15q0-1.25-.875-2.125T12 12t-2.125.875T9 15t.875 2.125T12 18h.1L11 19.1z");
}

</style>
