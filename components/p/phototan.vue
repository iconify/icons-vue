<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkyuwsbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phototan" /></template>
<style>
.kkyuwsbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.17 38.39h4.11v4.11h-4.11Zm-16.45 0h4.11v4.11h-4.11Zm8.22-8.22h4.12v4.11h-4.12Zm-8.22 0h4.11v4.11h-4.11Zm16.45-8.23h4.11v4.12h-4.11Zm-16.45 0h4.11v4.12h-4.11Zm-8.22 0h4.11v4.12H5.5Zm32.89 0h4.11v4.12h-4.11Zm0-8.22h4.11v4.11h-4.11Zm-16.45 0h4.12v4.11h-4.12Zm8.23-8.22h4.11v4.11h-4.11Zm-8.23 0h4.12v4.11h-4.12Zm-8.22 0h4.11v4.11h-4.11Zm-8.22 0h4.11v4.11H5.5Z");
}

</style>
