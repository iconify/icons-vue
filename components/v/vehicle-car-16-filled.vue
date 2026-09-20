<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u95idpb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-car-16-filled" /></template>
<style>
.u95idpb8h {
  fill: currentColor;
  d: path("m3.044 6l-.01.074A1.5 1.5 0 0 0 2 7.5v3A1.5 1.5 0 0 0 3.5 12h9a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.04-1.428L12.951 6h.549a.5.5 0 0 0 0-1h-.677l-.16-1.253A2 2 0 0 0 10.68 2H5.319a2 2 0 0 0-1.984 1.744L3.173 5H2.5a.5.5 0 0 0 0 1zm2.275-3h5.36a1 1 0 0 1 .992.873L11.943 6h-7.89l.274-2.128A1 1 0 0 1 5.319 3M5.25 9.749a.749.749 0 1 1 0-1.498a.749.749 0 0 1 0 1.498m5.498 0a.749.749 0 1 1 0-1.498a.749.749 0 0 1 0 1.498M12.497 13h-1.5v.25a.75.75 0 0 0 1.5 0zM5 13H3.5v.25a.75.75 0 0 0 1.5 0z");
}

</style>
