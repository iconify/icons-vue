<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-ty827q"/><path class="ubjs4q5ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-airlines" /></template>
<style>
.oq-ty827q {
  fill: currentColor;
  d: path("M14.05 6L5.8 18h11.54l2.25-12zm.45 8a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ubjs4q5ge {
  fill: currentColor;
  d: path("M17.34 18H5.8l8.25-12h5.54zM13 4L2 20h17l3-16zm1.5 5a2.5 2.5 0 0 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
