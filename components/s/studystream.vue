<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x78s5kdlm"/><path class="abf_6acni"/><path class="j5os3iyke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:studystream" /></template>
<style>
.abf_6acni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.957 29.125a2.41 2.41 0 0 0-3.416 0l-3.417 3.416c-.946.946-2.47.946-3.416 0s-.946-2.47 0-3.416l10.249-10.25a2.41 2.41 0 0 0 0-3.416L25.707 5.21a2.41 2.41 0 0 0-3.416 0L12.042 15.46a2.41 2.41 0 0 0 0 3.416l13.666 13.666");
}

.j5os3iyke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.125 8.626a2.41 2.41 0 0 1 0 3.416l-10.249 10.25a2.41 2.41 0 0 0 0 3.416m-.001 13.666a2.41 2.41 0 0 1 0-3.417L24 30.833");
}

.x78s5kdlm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.833 24l5.125 5.124a2.41 2.41 0 0 1 0 3.417L25.708 42.79a2.41 2.41 0 0 1-3.416 0L12.043 32.54a2.41 2.41 0 0 1 0-3.416L17.168 24");
}

</style>
