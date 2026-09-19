<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="omf6q7bff"/><path class="d8y2gfyll"/><path class="ya_9xjb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:queuebee" /></template>
<style>
.d8y2gfyll {
  d: path("M13.522 9.438a1.13 1.13 0 0 0-1.042 1.126V24c0 6.388 5.158 11.566 11.52 11.566S35.52 30.388 35.52 24S30.362 12.434 24 12.434c-1.826 0-3.626.435-5.252 1.271l-4.38-3.976a1.13 1.13 0 0 0-.847-.291");
}

.omf6q7bff {
  d: path("M24 2.5C12.126 2.5 2.5 12.126 2.5 24S12.126 45.5 24 45.5h17.639a1.167 1.167 0 0 0 .828-1.99l-3.785-3.803A21.5 21.5 0 0 0 45.5 24c0-11.874-9.626-21.5-21.5-21.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ya_9xjb1h {
  d: path("M28.404 13.312c-1.289 2.567-3.557 5.625-6.5 8.567c-2.941 2.942-6 5.21-8.566 6.5m21.067-9.343c-1.317 2.622-3.634 5.746-6.64 8.752c-3.005 3.005-6.129 5.322-8.75 6.639");
}

</style>
