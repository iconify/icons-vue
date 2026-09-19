<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rn47qix"/><path class="rqa6i68lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-video-file" /></template>
<style>
.rqa6i68lj {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zM6 20V4h7v5h5v11zm8-6l2-1.06v4.12L14 16v1c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1h4c.55 0 1 .45 1 1z");
}

.s2rn47qix {
  fill: currentColor;
  d: path("M13 9V4H6v16h12V9zm3 8.06L14 16v1c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v1l2-1.06z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
