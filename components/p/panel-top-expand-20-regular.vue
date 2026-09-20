<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q6xy51bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-top-expand-20-regular" /></template>
<style>
.q6xy51bul {
  fill: currentColor;
  d: path("m10.5 11.174l.874-.998a.5.5 0 0 1 .752.658l-1.75 2a.5.5 0 0 1-.752 0l-1.75-2a.5.5 0 1 1 .752-.658l.874.998V7.495a.5.5 0 0 1 1 0zM4 16a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2zm-1-2a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9h-5.5V8H17V6a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v2h5.5v1H3z");
}

</style>
