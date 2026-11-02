<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdixwhbnm"/><path class="ofj_qvbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ofj_qvbmk {
  d: path("M11 15h-1v6a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-6H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2H4v4h7a1 1 0 0 1 0 2m-5 0v5h2v-5Z");
}

.vdixwhbnm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.553 7.106l10-5A1 1 0 0 1 22 3v16a1 1 0 0 1-1.447.894l-10-5A1 1 0 0 1 10 14V8c0-.379.214-.725.553-.894");
}

</style>
