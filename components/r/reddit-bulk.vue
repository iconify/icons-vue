<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w5-sadc_h"/><path class="lodbygb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reddit-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lodbygb7u {
  d: path("m13.847 5l-.861 5.164a.999.999 0 1 1-1.972-.328l1-6A1 1 0 0 1 13 3h3.267a2.001 2.001 0 1 1 0 2ZM9.01 13a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-4.275 3.795A4 4 0 0 0 14.4 16.2a1 1 0 0 1 1.2 1.6a6 6 0 0 1-7.2 0a1 1 0 0 1 1.2-1.6a4 4 0 0 0 1.135.595");
}

.w5-sadc_h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 4a2 2 0 1 1 3.999-.001A2 2 0 0 1 16 4m-9.394 6.465c3.121-1.956 7.667-1.956 10.788 0a3.002 3.002 0 1 1 3.106 5.134c-.034 1.738-.966 3.273-2.291 4.354c-2.845 2.32-7.304 2.625-10.59 1.125c-1.258-.575-2.408-1.441-3.182-2.598c-.571-.852-.917-1.853-.937-2.881a3.002 3.002 0 0 1 .071-5.237a3 3 0 0 1 3.035.103");
}

</style>
