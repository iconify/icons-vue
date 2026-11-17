<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cd-idxjgh"/><path class="zb1k92bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:water-heater-bulk-round" /></template>
<style>
.cd-idxjgh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 10a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zb1k92bma {
  d: path("M10 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-5.5 7.5c0-.317-.068-.455-.219-.725a8 8 0 0 1-.175-.328c-.355-.71-.455-1.482-.217-2.245c.253-.808.837-1.463 1.486-1.983a1.002 1.002 0 0 1 1.606.585c.199.997.818 1.795 1.619 2.396a1 1 0 0 1 .107.093C15.71 12.296 16 13.626 16 15a4 4 0 0 1-.315 1.557A3.998 3.998 0 0 1 8 15c0-.789.22-1.632.791-2.205a.997.997 0 0 1 1.709.705m1.261-2.45c.002.276.136.516.266.75c.122.218.239.442.319.679c.11.328.154.676.154 1.021c0 .531-.21 1.039-.586 1.414a2 2 0 0 1-1.864.535A2 2 0 0 0 14 15c0-.788-.1-1.649-.664-2.249a6.5 6.5 0 0 1-1.575-1.701");
}

</style>
