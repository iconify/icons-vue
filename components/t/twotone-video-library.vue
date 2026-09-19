<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d726mibrn"/><path class="n8js1cqpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-video-library" /></template>
<style>
.d726mibrn {
  fill: currentColor;
  d: path("M8 16h12V4H8zm4-10.5l6 4.5l-6 4.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.n8js1cqpd {
  fill: currentColor;
  d: path("M4 6H2v14c0 1.1.9 2 2 2h14v-2H4zm16-4H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12zM12 5.5v9l6-4.5z");
}

</style>
