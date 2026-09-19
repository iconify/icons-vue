<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hbh6ehbhr"/><path class="n3-95z1kj"/><path class="iyq9tsbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:webex" /></template>
<style>
.hbh6ehbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.843 30.687c-1.977-5.4-2.825-9.59-2.847-12.874c-.075-2.542 1.633-4.293 3.768-4.325s3.357 1.75 3.898 3.467c1.477 4.69 1.373 12.892 4.774 12.913c1.936.012 2.996-2.271 4.05-5.69m3.711 10.354c-3.078 4.917-6.742 4.497-7.817 4.5c-1.299.002-6.246.646-9.537-8.345c-1.977-5.4-2.825-9.59-2.847-12.874c-.074-2.542 1.633-4.293 3.768-4.325s3.357 1.75 3.898 3.467c1.477 4.69 1.374 12.892 4.774 12.913c1.936.011 2.996-2.271 4.05-5.69m7.745-1.318c.826-3.621 2.306-5.397 3.574-5.056c3.22.864 1.93 6.109 7.14 5.408c6.4-1.517 1.006-14.273-7.527-14.254c-2.72.05-5.18 1.77-6.764 4.345M8.71 13.295c3.515-4.764 7.118-4.24 7.725-4.337c.517.087 4.883-.55 8.231 5.193");
}

.iyq9tsbgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.666 14.151c3.15 4.41 4.392 15.848 7.177 15.823c1.638-.015 2.734-3.235 3.676-7.213");
}

.n3-95z1kj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.888 13.6c7.78.131 2.374 14.523.95 18.03c-2.243 5.521-5.592 7.651-9.738 7.401c-10.516.443-9.176-21.736-14.664-21.228c-1.873.174-2.714 3.273-3.267 6.432");
}

</style>
