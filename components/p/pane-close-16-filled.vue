<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="ysfvf2ydg"/><path class="k4e7mccro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pane-close-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4e7mccro {
  d: path("M12 13.001a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2v6.002a2 2 0 0 0 2 2h8zm-3-1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h5v8.002z");
  fill: currentColor;
}

.ysfvf2ydg {
  d: path("M6.293 7.5H4.502a.5.5 0 0 0 0 1h1.79l-.646.647a.5.5 0 1 0 .708.707l1.5-1.5a.5.5 0 0 0 0-.707l-1.5-1.5a.5.5 0 1 0-.708.707l.647.646z");
  fill: currentColor;
}

</style>
