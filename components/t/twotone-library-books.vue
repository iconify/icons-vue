<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ena08_y"/><path class="jv-1_ac6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-library-books" /></template>
<style>
.jv-1_ac6g {
  fill: currentColor;
  d: path("M4 22h14v-2H4V6H2v14c0 1.1.9 2 2 2M6 4v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2m14 12H8V4h12zM10 9h8v2h-8zm0 3h4v2h-4zm0-6h8v2h-8z");
}

.p5ena08_y {
  fill: currentColor;
  d: path("M8 16h12V4H8zm2-10h8v2h-8zm0 3h8v2h-8zm0 3h4v2h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
