<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk6sowb4c"/><path class="s1klgg5zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-question-answer" /></template>
<style>
.hk6sowb4c {
  fill: currentColor;
  d: path("M15 11V4H4v8.17l.59-.58l.58-.59H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s1klgg5zy {
  fill: currentColor;
  d: path("M21 6h-2v9H6v2c0 .55.45 1 1 1h11l4 4V7c0-.55-.45-1-1-1m-5 7c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v14l4-4zM4.59 11.59l-.59.58V4h11v7H5.17z");
}

</style>
