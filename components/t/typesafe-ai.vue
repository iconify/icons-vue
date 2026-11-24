<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":373};
const content = `<path class="d02uk1bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:typesafe-ai" /></template>
<style>
.d02uk1bli {
  d: path("M198.067 45.464v64.268l57.917 37.576l.016 142.309l-127.992 83.04l-70.044-45.448V261.17L0 223.579V83.072l5.512-3.603L128.008 0zM92.248 320.641l35.729 23.197l93.692-60.82l-35.713-23.167zm47.856-160.212v63.165L82.14 261.202v37.172l91.72-59.516V138.52zm57.963 78.444l33.726 21.894V160.429l-33.726-21.894zM34.316 217.011l35.744 23.198l35.728-23.198l-35.728-23.152zM24.223 96.16v98.615l33.71-21.894v-63.165l57.979-37.623v-35.45zm57.932 76.69l33.741 21.893V160.43l-33.71-21.91v34.332zm10.093-56.597l35.76 23.197l35.713-23.182l-35.713-23.198zm47.871-44.16l33.741 21.909V58.6l-33.74-21.97z");
}

</style>
