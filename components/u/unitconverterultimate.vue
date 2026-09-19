<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkk-tw0ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unitconverterultimate" /></template>
<style>
.gkk-tw0ux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.66 5.69v5.24H31v8.66H13.69l-.18 4.95L4.5 15l9.16-9.34Zm20.41 17.76l9.43 9.43l-9.43 9.43v-5.1H16.75v-8.66h17.32z");
}

</style>
