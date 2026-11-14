<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hf5a8ebse"/><path class="ioe5kn5bp"/><path class="db5n4obwn"/><path class="hvxp8gb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:popcorn-box" /></template>
<style>
.db5n4obwn {
  d: path("M9.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.hf5a8ebse {
  d: path("M5 9h14l-1.5 11.5h-11Zm4.5 0l.5 11.5M14.5 9L14 20.5");
}

.hvxp8gb1n {
  d: path("M14 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ioe5kn5bp {
  d: path("M5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
