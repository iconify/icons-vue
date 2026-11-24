<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ikjuefb_a"/><path class="ksvke4bkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-headset-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ikjuefb_a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 10a5 5 0 1 1 10.001.001A5 5 0 0 1 7 10m13 12H4a1 1 0 0 1-1-1c0-.829.336-1.577.865-2.203c.552-.651 1.272-1.14 2.031-1.52C7.741 16.355 9.953 16 12 16s4.259.355 6.104 1.277c.759.38 1.479.869 2.031 1.52c.529.626.865 1.374.865 2.203a1 1 0 0 1-1 1");
}

.ksvke4bkj {
  d: path("M2 10a1 1 0 0 1 1-1h1.061a8 8 0 0 1 7.938-7a8 8 0 0 1 7.94 6.997V9H21a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1a1 1 0 0 1-1 1h-2a1 1 0 0 1 0-2v-4a6 6 0 0 0-12 0v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm1 11c0-.829.336-1.577.865-2.203c.552-.651 1.272-1.14 2.031-1.52c3.416-1.707 8.792-1.707 12.208 0c.759.38 1.479.869 2.031 1.52c.529.626.865 1.374.865 2.203a1 1 0 0 1-2 0c0-.343-.176-.655-.392-.911c-.376-.444-.883-.765-1.398-1.023C15.653 18.288 13.725 18 12 18s-3.653.288-5.21 1.066c-.515.258-1.022.579-1.398 1.023c-.216.256-.392.568-.392.911a1 1 0 0 1-2 0");
}

</style>
