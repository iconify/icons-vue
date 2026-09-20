<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="fc5y0hbbn"/><path class="uyjwjobxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pane-close-20-filled" /></template>
<style>
.fc5y0hbbn {
  d: path("M9.179 10.5l-.998.874a.5.5 0 1 0 .658.752l2-1.75a.5.5 0 0 0 0-.752l-2-1.75a.5.5 0 1 0-.658.752l.998.874H5.5a.5.5 0 0 0 0 1h3.679z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.uyjwjobxa {
  d: path("M16 16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12zM12 5v10H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h8z");
  fill: currentColor;
}

</style>
