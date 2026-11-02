<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dxl_10b1n"/><path class="owxvw2i6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dxl_10b1n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 16a4 4 0 1 1 8 0a4 4 0 0 1-8 0M2 18a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.owxvw2i6k {
  d: path("M8 9c0-.601.111-1.205.382-1.746c.271-.543.716-1.007 1.302-1.203l9-3c1.034-.344 2.308-.104 2.961.827c.231.33.355.719.355 1.122v11a1 1 0 0 1-2 0V5.017a.3.3 0 0 0-.078-.053c-.185-.092-.415-.079-.606-.015l-9 3l.003-.001c-.069.043-.114.131-.149.201c-.13.262-.17.561-.17.851v9a1 1 0 0 1-2 0Z");
}

</style>
