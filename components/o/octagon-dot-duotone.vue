<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z23j5nbms"/><path class="xii-u1kii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-dot-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xii-u1kii {
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
}

.z23j5nbms {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5645 2C15.4927 2 16.3827 2.369 17.0391 3.0254L20.9746 6.9609C21.631 7.6173 22 8.5073 22 9.4355L22 14.5645C22 15.4927 21.631 16.3827 20.9746 17.0391L17.0391 20.9746C16.3827 21.631 15.4927 22 14.5645 22L9.4355 22C8.5073 22 7.6173 21.631 6.9609 20.9746L3.0254 17.0391C2.369 16.3827 2 15.4927 2 14.5645L2 9.4355C2 8.5073 2.369 7.6173 3.0254 6.9609L6.9609 3.0254C7.6173 2.369 8.5073 2 9.4355 2L14.5645 2Z");
}

</style>
