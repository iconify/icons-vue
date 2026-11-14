<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gat6lxbac"/><path class="j8hb307di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-goal" /></template>
<style>
.gat6lxbac {
  d: path("M12.034 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.75 6.5-4.75c.898 0 1.752.124 2.528.354M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm8.75 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.j8hb307di {
  d: path("M16.75 17.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
