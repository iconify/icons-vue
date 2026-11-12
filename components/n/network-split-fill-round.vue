<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkbo8pbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-fill-round" /></template>
<style>
.gkbo8pbxz {
  fill: currentColor;
  d: path("M13 7.829V11h1a5 5 0 0 1 5 5v1.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L17 17.586V16a3 3 0 0 0-3-3h-4c-.796 0-1.559.316-2.121.879A3 3 0 0 0 7 16v1.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.413.001h-.001l-3-3.001a.999.999 0 1 1 1.414-1.414L5 17.586V16a5 5 0 0 1 5-5h1V7.829a3 3 0 1 1 2 0");
}

</style>
