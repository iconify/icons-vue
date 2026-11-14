<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ymlh1hb_d"/><path class="gmev8bciy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moon-cloud-fog" /></template>
<style>
.gmev8bciy {
  d: path("M12.75 5.5a3.5 3.5 0 1 1 4.5 4a4.5 4.5 0 0 0-4.5-4ZM4 17.5h12M7.5 21h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymlh1hb_d {
  d: path("M6.5 14a3.5 3.5 0 0 1 .25-7a4.5 4.5 0 0 1 8 .75A3.25 3.25 0 0 1 15.5 14Z");
}

</style>
