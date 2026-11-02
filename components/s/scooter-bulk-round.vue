<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="olk9j-t8r"/><path class="xv2afo8gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scooter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.olk9j-t8r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.236 16.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m14 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M4.293 18.707a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m14 0a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.xv2afo8gx {
  d: path("m18.18 5l1.806 10.836a.999.999 0 1 1-1.972.328l-.827-4.96c-.827.451-1.383 1.627-1.729 2.457c-.231.555-.432 1.124-.633 1.692c-.267.756-.524 1.531-.908 2.237c-.402.74-1.015 1.409-1.917 1.41H7a1 1 0 0 1 0-2h4.913c.103-.103.178-.238.247-.365c.146-.268.263-.551.373-.835c.144-.368.275-.741.406-1.114c.718-2.03 1.66-4.78 3.91-5.509l-.835-5.013A.998.998 0 0 1 17 3h4a1 1 0 0 1 0 2Z");
}

</style>
