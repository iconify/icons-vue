<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv24i8obd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:planner-banner-ad-pt-outline" /></template>
<style>
.uv24i8obd {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12V4H6zm1-2h10l-3.45-4.5l-2.3 3l-1.55-2zm-1 2V4z");
}

</style>
