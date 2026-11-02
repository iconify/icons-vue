<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sn-kq-mjg"/><path class="mv6f7uqql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:strikethrough-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mv6f7uqql {
  d: path("M13.789 5.422A4.001 4.001 0 0 0 8.8 11.4a1 1 0 0 1-1.6 1.2A6 6 0 0 1 12 3a5.9 5.9 0 0 1 2.683.633A5.9 5.9 0 0 1 16.8 5.4a1 1 0 0 1-1.6 1.2a3.95 3.95 0 0 0-1.411-1.178m3.903 7.681A6 6 0 0 1 7.2 18.6a1.002 1.002 0 0 1 .68-1.593a1 1 0 0 1 .92.393a4 4 0 1 0 6.4-4.8a1 1 0 0 1 1.6-1.2a6 6 0 0 1 .892 1.703");
}

.sn-kq-mjg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 11h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
