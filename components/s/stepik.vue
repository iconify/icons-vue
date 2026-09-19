<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6ku585ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stepik" /></template>
<style>
.s6ku585ab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.582 40.256a7.663 7.663 0 0 0 10.836 0l10.837-10.838a7.663 7.663 0 0 0-10.837-10.836L18.582 29.417A7.663 7.663 0 0 1 7.743 18.582L18.582 7.743a7.663 7.663 0 0 1 10.837 0");
}

</style>
