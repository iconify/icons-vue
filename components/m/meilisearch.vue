<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":150};
const content = `<defs><linearGradient id="SVGN4tMQcEy" x1="153.821%" x2="19.172%" y1="-7.638%" y2="89.239%"><stop offset="0%" class="a0yr657mp"/><stop offset="100%" class="hkvg0-h-j"/></linearGradient><linearGradient id="SVGRI2TBe2w" x1="117.325%" x2="-17.323%" y1="-7.638%" y2="89.238%"><stop offset="0%" class="a0yr657mp"/><stop offset="100%" class="hkvg0-h-j"/></linearGradient><linearGradient id="SVGpP8XvdkJ" x1="80.828%" x2="-53.821%" y1="-7.638%" y2="89.238%"><stop offset="0%" class="a0yr657mp"/><stop offset="100%" class="hkvg0-h-j"/></linearGradient></defs><path fill="url(#SVGN4tMQcEy)" class="mp2_g3bib"/><path fill="url(#SVGRI2TBe2w)" class="g7ggmjmve"/><path fill="url(#SVGpP8XvdkJ)" class="sb2in4p9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:meilisearch" /></template>
<style>
.a0yr657mp {
  stop-color: var(--svg-color--ff5caa, #ff5caa);
}

.g7ggmjmve {
  d: path("m69.386 149.289l47.297-121.012A44.46 44.46 0 0 1 158.095 0h28.514l-47.297 121.012a44.46 44.46 0 0 1-41.411 28.277z");
}

.hkvg0-h-j {
  stop-color: var(--svg-color--ff4e62, #ff4e62);
}

.mp2_g3bib {
  d: path("M0 149.288L47.297 28.277A44.46 44.46 0 0 1 88.708 0h28.515L69.926 121.012a44.46 44.46 0 0 1-41.411 28.276z");
}

.sb2in4p9v {
  d: path("m138.777 149.289l47.297-121.012A44.46 44.46 0 0 1 227.484 0H256l-47.297 121.012a44.46 44.46 0 0 1-41.412 28.277z");
}

</style>
