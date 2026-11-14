<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qse7auvxl"/><path class="zwbkse5vc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-station-settings" /></template>
<style>
.qse7auvxl {
  d: path("M8.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwbkse5vc {
  d: path("m4.5 20.5l5.5-12l2.666 5.818M5 3.5a5.5 5.5 0 0 0 0 7m10-7a5.5 5.5 0 0 1 0 7m2.233 4.859l.103-1.05h1.328l.103 1.05l1.136.656l.961-.435l.664 1.15l-.857.614v1.312l.857.614l-.664 1.15l-.961-.435l-1.136.656l-.103 1.05h-1.328l-.103-1.05l-1.136-.656l-.961.435l-.664-1.15l.857-.614v-1.312l-.857-.614l.664-1.15l.961.435Z");
}

</style>
