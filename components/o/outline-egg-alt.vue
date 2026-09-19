<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-tisonbz"/><circle class="zaponzdgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-egg-alt" /></template>
<style>
.j-tisonbz {
  fill: currentColor;
  d: path("M19 9c-2-2-3.01-7-9.03-7C4.95 2 1.94 6 2 11.52S6.96 19 9.97 19c2.01 0 2.01 3 6.02 3C19 22 22 19 22 15.02C22 12 21.01 11 19 9m-3.01 11c-1.49 0-1.96-.5-2.68-1.26c-.65-.69-1.65-1.74-3.34-1.74c-1.64 0-5.92-.99-5.97-5.5c-.03-2.51.68-4.62 1.99-5.95C7.01 4.52 8.35 4 9.97 4c3.34 0 4.51 1.86 5.86 4.02c.55.88 1.07 1.71 1.76 2.39c1.9 1.89 2.41 2.4 2.41 4.61c0 2.85-2.12 4.98-4.01 4.98");
}

.zaponzdgz {
  cx: 12px;
  cy: 12px;
  r: 3.5px;
  fill: currentColor;
}

</style>
