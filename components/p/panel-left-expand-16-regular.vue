<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gnpikw8xj"/><path class="h732d-kpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-expand-16-regular" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gnpikw8xj {
  d: path("m9.647 9.147l.646-.647H8.502a.5.5 0 0 1 0-1h1.791l-.646-.646a.5.5 0 1 1 .707-.707l1.5 1.5a.5.5 0 0 1 0 .707l-1.5 1.5a.5.5 0 1 1-.707-.707");
}

.h732d-kpj {
  d: path("M2 4.999a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6.002a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v6.002a1 1 0 0 0 1 1h2.002V4zm3.002 0v8.002H12a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1z");
}

</style>
