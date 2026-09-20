<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vu-xkxsfg"/><path class="dfzkxi56c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:unite-square-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dfzkxi56c {
  d: path("M216 88h-48V40a8 8 0 0 0-8-8H40a8 8 0 0 0-8 8v120a8 8 0 0 0 8 8h48v48a8 8 0 0 0 8 8h120a8 8 0 0 0 8-8V96a8 8 0 0 0-8-8m-8 120H104v-48a8 8 0 0 0-8-8H48V48h104v48a8 8 0 0 0 8 8h48Z");
}

.vu-xkxsfg {
  d: path("M216 96v120H96v-56H40V40h120v56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
