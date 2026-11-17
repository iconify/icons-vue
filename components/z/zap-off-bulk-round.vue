<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ckpf39k9d"/><path class="scc1kvjkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-bulk-round" /></template>
<style>
.ckpf39k9d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.275 15.032L8.826 7.584l2.896-3.641A1.697 1.697 0 0 1 14.75 5v3a.997.997 0 0 0 1 1H17a1.966 1.966 0 0 1 1.538 3.188Zm-1.88 2.363l-2.117 2.662A1.699 1.699 0 0 1 9.25 19v-3a.997.997 0 0 0-1-1H7a1.966 1.966 0 0 1-1.538-3.188l1.485-1.865Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.scc1kvjkf {
  d: path("m2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
