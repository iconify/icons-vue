<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="crtky0bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-45-right-16-filled" /></template>
<style>
.crtky0bbm {
  fill: currentColor;
  d: path("M1.22 6.219a.75.75 0 0 1 1.061 0l6.22 6.221v-.689a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h.69l-6.22-6.222a.75.75 0 0 1 0-1.06m9.5-.5a.75.75 0 0 1 1.061 0l1.72 1.72v-.688a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h.691l-1.721-1.722a.75.75 0 0 1 0-1.06m-.758-4.662a.751.751 0 0 1 .98.98l-2.499 6A.751.751 0 0 1 7.06 7.46l.505-1.216l-1.81-1.81l-1.215.507a.75.75 0 0 1-.576-1.384zM7.25 3.81l.937.937l.67-1.606z");
}

</style>
