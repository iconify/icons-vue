<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgop8vbfg"/><path class="j-kgtabyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-slideshow" /></template>
<style>
.cgop8vbfg {
  fill: currentColor;
  d: path("M5 19h14V5H5zm5-11l5 4l-5 4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j-kgtabyu {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zM10 8v8l5-4z");
}

</style>
