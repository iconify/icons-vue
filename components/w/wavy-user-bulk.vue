<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bof_mac4i"/><path class="w_dsri1hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-user-bulk" /></template>
<style>
.bof_mac4i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.53 3.783c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747c2.376 1.655 2.376 5.285 0 6.94c.617 2.786-1.961 5.364-4.747 4.747c-1.655 2.376-5.285 2.376-6.94 0c-2.786.617-5.364-1.961-4.747-4.747c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747");
}

.cuyn6tgcc {
  fill: currentColor;
}

.w_dsri1hp {
  d: path("M9.236 7.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414M6 18.982a6 6 0 0 1 12 0l.007.198a1 1 0 0 1-1.999.068l-.007-.214L16 19a3.97 3.97 0 0 0-1.172-2.828a4 4 0 0 0-3.597-1.097A3.99 3.99 0 0 0 8 19l-.001.034l-.007.214a1 1 0 1 1-1.999-.068Z");
}

</style>
