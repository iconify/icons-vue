<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ugozecbbz"/><g class="xtpeb-edw"><path class="s5ao597ql"/><path class="nsg7l2cph"/><path class="jd818u1tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-alphabetically-bold-duotone" /></template>
<style>
.jd818u1tz {
  d: path("M13 6.25C13.4142 6.25 13.75 6.58579 13.75 7C13.75 7.41421 13.4142 7.75 13 7.75H3C2.58579 7.75 2.25 7.41421 2.25 7C2.25 6.58579 2.58579 6.25 3 6.25H13Z");
}

.nsg7l2cph {
  d: path("M10 11.25C10.4142 11.25 10.75 11.5858 10.75 12C10.75 12.4142 10.4142 12.75 10 12.75H3C2.58579 12.75 2.25 12.4142 2.25 12C2.25 11.5858 2.58579 11.25 3 11.25H10Z");
}

.s5ao597ql {
  d: path("M8 16.25C8.41421 16.25 8.75 16.5858 8.75 17C8.75 17.4142 8.41421 17.75 8 17.75H3C2.58579 17.75 2.25 17.4142 2.25 17C2.25 16.5858 2.58579 16.25 3 16.25H8Z");
}

.ugozecbbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.1841 6.69223C17.063 6.42309 16.7953 6.25 16.5002 6.25C16.2051 6.25 15.9374 6.42309 15.8162 6.69223L11.3162 16.6922C11.1463 17.07 11.3147 17.514 11.6924 17.6839C12.0701 17.8539 12.5141 17.6855 12.6841 17.3078L14.1215 14.1136H18.8789L20.3162 17.3078C20.4862 17.6855 20.9302 17.8539 21.308 17.6839C21.6857 17.514 21.8541 17.07 21.6841 16.6922L17.1841 6.69223ZM16.5002 8.82764L14.7965 12.6136H18.2039L16.5002 8.82764Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
