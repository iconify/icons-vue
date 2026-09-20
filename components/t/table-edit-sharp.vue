<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8a4a5bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-edit-sharp" /></template>
<style>
.f8a4a5bhl {
  fill: currentColor;
  d: path("M3 14V9h8v5zm0-7V3h18v4zm0 14v-5h8v5zm10-7V9h7.15l-5.025 5zm0 8v-3.075l6.575-6.55l3.075 3.05L16.075 22zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
