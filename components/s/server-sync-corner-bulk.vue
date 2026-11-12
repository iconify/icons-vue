<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sowt4_0jd"/><path class="f06omweho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-sync-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f06omweho {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM20 13a1 1 0 0 1 2 0v3a.997.997 0 0 1-1 1h-3a1 1 0 0 1 0-2h.748a5 5 0 0 0-.195-.106l-.003-.001a3.47 3.47 0 0 0-3.102.001a3.5 3.5 0 0 0-1.552 1.549l-.002.004a1 1 0 0 1-1.791-.889a5.4 5.4 0 0 1 1.028-1.427a5.47 5.47 0 0 1 6.316-1.025l.003.001l.004.002q.282.141.546.314ZM7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM14 21.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .963-.999h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894A5.465 5.465 0 0 1 14 21.577");
}

.sowt4_0jd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8 8v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1");
}

</style>
