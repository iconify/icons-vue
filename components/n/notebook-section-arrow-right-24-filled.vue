<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wciux4v9q"/><path class="xkncz6byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notebook-section-arrow-right-24-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wciux4v9q {
  d: path("M15.648 2.007L15.75 2a.75.75 0 0 1 .743.648l.007.102v8.327a6.502 6.502 0 0 0-5.004 8.92H9.25A2.25 2.25 0 0 1 7 17.746V6.25A2.25 2.25 0 0 1 9.25 4L15 3.999V2.75a.75.75 0 0 1 .648-.743");
}

.xkncz6byk {
  d: path("M23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-8.5-.5a.5.5 0 0 0 0 1h4.793l-1.647 1.647a.5.5 0 0 0 .708.707l2.5-2.5a.5.5 0 0 0 0-.707l-2.5-2.5a.5.5 0 0 0-.708.707L19.293 17z");
}

</style>
