<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gnqo1tbyt"/><path class="x3w8deb5n"/><path class="niuy-xgia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-48-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gnqo1tbyt {
  d: path("M16.668 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0z");
  fill: currentColor;
}

.niuy-xgia {
  d: path("M36.168 27.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7z");
  fill: currentColor;
}

.x3w8deb5n {
  d: path("M28.168 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0z");
  fill: currentColor;
}

</style>
