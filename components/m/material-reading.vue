<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ni8knu_3d"/><path class="iftidybvw"/><path class="ty9320bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:material-reading" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iftidybvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.63 13.716c2.367 3.918 3 6.74 2.653 15.282c0 0 1.823 2.322 2.081 7.686M16.621 29.5v6.428m7.53-6.428v6.428M9.48 39.841c0-16.391 7.514-18.509 8.152-18.784c-1.76-2.05-5.346-5.583-7.21-6.49c0 0-2.334 3.755.3 15.263");
}

.ni8knu_3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.635 13.734c-.03-.18-.192-.26-.327-.26c-.636 0-4.42 5.094-6.97 9.055c0 0 3.777 3.542 6.867 9.512c0 0 1.732-10.647.43-18.307");
}

.ty9320bxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.422 14.568c4.091 1.45 7.943 3.21 11.59 5.39c3.18-.914 6.883-.25 8.401.747");
}

</style>
