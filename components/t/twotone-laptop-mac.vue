<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_08bu7ae"/><path class="tmbg20bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-laptop-mac" /></template>
<style>
.b_08bu7ae {
  fill: currentColor;
  d: path("M4 5h16v11H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tmbg20bhn {
  fill: currentColor;
  d: path("M20 18c1.1 0 1.99-.9 1.99-2L22 5c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2H0c0 1.1.9 2 2 2h20c1.1 0 2-.9 2-2zM4 5h16v11H4zm8 14c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
