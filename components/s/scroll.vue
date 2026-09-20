<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="l4iqfpxil"/><path class="bwbz-gbbt"/><path class="xlcc9bzbe"/><path class="l05wbxb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:scroll" /></template>
<style>
.bwbz-gbbt {
  fill: var(--svg-color--e39f3d, #e39f3d);
  d: path("M8 10h24V8H10L8 7z");
}

.l05wbxb-l {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M12 4a2 2 0 1 1-4.001-.001A2 2 0 0 1 12 4M6 32a2 2 0 1 1-4.001-.001A2 2 0 0 1 6 32m24-17a1 1 0 0 1-1 1H11a1 1 0 0 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H11a1 1 0 1 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H11a1 1 0 1 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H11a1 1 0 1 1 0-2h18a1 1 0 0 1 1 1");
}

.l4iqfpxil {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M32 0H10a4 4 0 0 0-4 4v24H4a4 4 0 0 0 0 8h24a4 4 0 0 0 4-4V8a4 4 0 0 0 0-8");
}

.xlcc9bzbe {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M10 0a4 4 0 0 0-4 4v24.555A3.96 3.96 0 0 0 4 28a4 4 0 1 0 4 4V7.445C8.59 7.789 9.268 8 10 8a4 4 0 0 0 0-8");
}

</style>
