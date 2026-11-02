<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d4n4mgb5a"/><path class="lne1cyb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telegram-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d4n4mgb5a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.638 10.068l18-7a1 1 0 0 1 1.332 1.175l-4 16a1 1 0 0 1-1.677.464l-4.185-4.185L9.8 19.6a1 1 0 0 1-1.749-.284l-1.869-5.607l-3.629-1.815a.999.999 0 0 1 .085-1.826");
}

.lne1cyb4m {
  d: path("M14.707 11.707L12.414 14l.293.293A1 1 0 0 1 12.8 15.6l-3 4a1 1 0 0 1-1.749-.284l-2-6A.999.999 0 0 1 7.2 12.02c.35.072.636.325.749.664l1.396 4.189l1.335-1.779l-.387-.387a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
