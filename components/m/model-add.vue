<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pkeva3bti"/><path class="yimmmv_ip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:model-add" /></template>
<style>
.pkeva3bti {
  d: path("M12.164 19.882L11 20.5l-8-4.25v-9.5l8-4.25l8 4.25v5.441");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yimmmv_ip {
  d: path("M3 6.75L11 11l8-4.25M11 11v9.5m7-5.5v6m-3-3h6");
}

</style>
