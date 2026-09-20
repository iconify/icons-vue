<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":305};
const content = `<defs><linearGradient id="SVGeY8NEnFa" x1="50%" x2="50%" y1="16.62%" y2="119.283%"><stop offset="0%" class="g_gp7lgqe"/><stop offset="82%" class="sav6x4bmf"/></linearGradient><linearGradient id="SVGoXiXXbjr" x1="41.18%" x2="67.714%" y1="31.16%" y2="78.678%"><stop offset="0%" class="g_gp7lgqe"/><stop offset="62%" class="sav6x4bmf"/></linearGradient></defs><circle fill="url(#SVGeY8NEnFa)" class="qu_c3bbrz"/><path fill="url(#SVGoXiXXbjr)" class="pjvm2ab5o"/><path class="c54osrbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:opsgenie" /></template>
<style>
.c54osrbkw {
  fill: var(--svg-color--2684ff, #2684ff);
  d: path("M134.476 302.953a366.65 366.65 0 0 0 120.44-125.897a8.527 8.527 0 0 0-3.667-11.81l-57.64-28.265a8.527 8.527 0 0 0-11.127 3.41A284.6 284.6 0 0 1 58.845 252.305a366.7 366.7 0 0 0 62.67 50.649a12.24 12.24 0 0 0 12.961 0");
}

.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.pjvm2ab5o {
  d: path("M121.516 302.953A366.9 366.9 0 0 1 1.076 177.056a8.527 8.527 0 0 1 3.71-11.81l57.597-28.265a8.527 8.527 0 0 1 11.128 3.41a284.75 284.75 0 0 0 123.636 111.913a368.8 368.8 0 0 1-62.67 50.649a12.24 12.24 0 0 1-12.961 0");
}

.qu_c3bbrz {
  cx: 127.996px;
  cy: 76.058px;
  r: 76.058px;
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

</style>
