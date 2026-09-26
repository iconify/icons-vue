<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qkza15bef"/><path class="kjdy_6b8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kjdy_6b8e {
  d: path("M9.5 8C9.5 8.8284 8.8284 9.5 8 9.5C7.1716 9.5 6.5 8.8284 6.5 8C6.5 7.1716 7.1716 6.5 8 6.5C8.8284 6.5 9.5 7.1716 9.5 8Z");
}

.qkza15bef {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 5C1 2.790861 2.790861 1 5 1L11.171573 1C11.967223 1 12.730285 1.316071 13.292894 1.87868L22.12132 10.707107C23.292893 11.87868 23.292893 13.778174 22.12132 14.949747L14.949747 22.12132C13.778174 23.292893 11.87868 23.292893 10.707107 22.12132L1.87868 13.292894C1.316071 12.730285 1 11.967223 1 11.171573Z");
}

</style>
