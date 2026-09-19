<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njrm9zfbx"/><path class="eehrrrlqw"/><path class="pa22ib4sy"/><path class="x2zxttsnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-10k" /></template>
<style>
.eehrrrlqw {
  fill: currentColor;
  d: path("M5 9h2.5v6H6v-4.5H5V19h14v-4h-1.75l-1.75-2.25V15H14V9h1.5v2.25L17.25 9H19V5H5zm3.5 1c0-.55.45-1 1-1H12c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1H9.5c-.55 0-1-.45-1-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.njrm9zfbx {
  fill: currentColor;
  d: path("M10 10.5h1.5v3H10zm9 4.5V9l-2.25 3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pa22ib4sy {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 6v10H5v-8.5h1V15h1.5V9H5V5h14z");
}

.x2zxttsnq {
  fill: currentColor;
  d: path("M15.5 11.25V9H14v6h1.5v-2.25L17.25 15H19l-2.25-3L19 9h-1.75zM9.5 15H12c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1H9.5c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-4.5h1.5v3H10z");
}

</style>
