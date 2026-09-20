<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dpmq1zb3d"/><path class="jzu_hbclg"/><path class="yagljhbma"/><path class="dbzj4vbfx"/><path class="c70ez2pse"/><path class="w7oqjqb9f"/><path class="r-9yt_crs"/><path class="o52wx7a_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-up-24-filled" /></template>
<style>
.c70ez2pse {
  d: path("M8 14.5v-5H3.75a.75.75 0 0 0-.75.75v4.25h5z");
  fill: currentColor;
}

.dbzj4vbfx {
  d: path("M9.5 16h5v5h-5v-5z");
  fill: currentColor;
}

.dpmq1zb3d {
  d: path("M20.25 4.5a.75.75 0 0 0 0-1.5H3.75a.75.75 0 1 0 0 1.5h16.5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.jzu_hbclg {
  d: path("M20.78 9.72c.141.14.22.331.22.53v4.25h-5v-5h4.25a.75.75 0 0 1 .53.22z");
  fill: currentColor;
}

.o52wx7a_z {
  d: path("M14.81 9.248a.75.75 0 0 1-1.058.063l-1.002-.89v2.829a.75.75 0 0 1-1.5 0V8.42l-1.002.89a.75.75 0 0 1-.996-1.12l2.25-2a.75.75 0 0 1 .996 0l2.25 2a.75.75 0 0 1 .063 1.058z");
  fill: currentColor;
}

.r-9yt_crs {
  d: path("M16 16h5v1.75A3.25 3.25 0 0 1 17.75 21H16v-5z");
  fill: currentColor;
}

.w7oqjqb9f {
  d: path("M3 16h5v5H6.25A3.25 3.25 0 0 1 3 17.75V16z");
  fill: currentColor;
}

.yagljhbma {
  d: path("M14.5 14.5v-4.018c-.25.036-.506.018-.75-.054v.822a1.75 1.75 0 1 1-3.5 0v-.822c-.244.072-.5.09-.75.054V14.5h5z");
  fill: currentColor;
}

</style>
