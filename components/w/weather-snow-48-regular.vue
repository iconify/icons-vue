<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn15o_2wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-snow-48-regular" /></template>
<style>
.gn15o_2wp {
  fill: currentColor;
  d: path("M19.5 36a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M15 34a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M24.001 8c6.337 0 9.932 4.195 10.455 9.26h.16c4.078 0 7.384 3.298 7.384 7.365s-3.306 7.365-7.384 7.365h-21.23c-4.078 0-7.384-3.297-7.384-7.365s3.306-7.365 7.385-7.365h.16C14.072 12.161 17.664 8 24 8m0 2.495c-4.26 0-7.975 3.448-7.975 8.21c0 .755-.656 1.348-1.407 1.348h-1.42c-2.595 0-4.698 2.113-4.698 4.72c0 2.608 2.103 4.722 4.697 4.722h21.606c2.594 0 4.697-2.114 4.697-4.721s-2.102-4.722-4.697-4.722h-1.42c-.751 0-1.408-.592-1.408-1.346c0-4.824-3.714-8.21-7.975-8.21");
}

</style>
