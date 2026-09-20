<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xcn9kjb0c"/><path class="rv2i6mbtp"/><path class="g6phfwb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:set-top-stack-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g6phfwb1w {
  d: path("M9 20a2 2 0 0 1-1.937-1.5h9.187a4.25 4.25 0 0 0 4.25-4.25V9.063A2 2 0 0 1 22 11v3.25A5.75 5.75 0 0 1 16.25 20H9z");
  fill: currentColor;
}

.rv2i6mbtp {
  d: path("M6.5 17.5A2 2 0 0 1 4.563 16H15.5a2.5 2.5 0 0 0 2.5-2.5V6.563A2 2 0 0 1 19.5 8.5v5a4 4 0 0 1-4 4h-9z");
  fill: currentColor;
}

.xcn9kjb0c {
  d: path("M4 4a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H4zm5.5 2.1a.5.5 0 0 1 .447.276l.88 1.761l1.735.217a.5.5 0 0 1 .258.88l-1.266 1.055l.434 1.953a.5.5 0 0 1-.753.532L9.5 11.69l-1.735 1.084a.5.5 0 0 1-.753-.532l.434-1.953L6.18 9.234a.5.5 0 0 1 .258-.88l1.734-.217l.88-1.76A.5.5 0 0 1 9.5 6.1z");
  fill: currentColor;
}

</style>
