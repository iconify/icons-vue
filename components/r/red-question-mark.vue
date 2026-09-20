<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="gkcsbqbth"/><circle class="l9h30jb2k"/><path class="eomen_bjf"/><path class="rss8zpbnq"/><path class="lelilub1p"/><path class="y2w3b8bvc"/><path class="g7zm4zbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:red-question-mark" /></template>
<style>
.eomen_bjf {
  fill: var(--svg-color--fff, #fff);
  d: path("M55.1 108.4c1.2-1.8 3.8-3.3 6.5-3.7c.7-.1 1.3-.1 1.9.1c.4.2.8.6.5 1c-.2.4-.7.5-1.1.6c-2.5.7-4.8 2.4-6.2 4.4c-.5.8-1.4 2.9-2.4 2.4c-1-.7-.8-2.6.8-4.8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7zm4zbzi {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.6 15.9C43 11.7 49.5 8.7 56 8.3c1.6-.1 3.2 0 4.5.7c1 .5 1.7 1.6 1 2.6c-.6.8-1.8 1.1-2.8 1.3c-6.1 1.2-12 4.7-15.9 9.3c-1.5 1.8-4 6.8-6.2 5.2c-2.3-1.9-1.2-6.4 3-11.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gkcsbqbth {
  cx: 62.5px;
  cy: 112px;
  r: 12px;
  fill: var(--svg-color--c33, #c33);
}

.l9h30jb2k {
  cx: 60.9px;
  cy: 112px;
  r: 10.3px;
  fill: var(--svg-color--f44336, #f44336);
}

.lelilub1p {
  fill: var(--svg-color--c33, #c33);
  d: path("M89.5 12.2C83.4 6.7 75 4 64.2 4c-1.2 0-2.3 0-3.4.1c9.1.5 16.4 3.2 21.8 8.1c6.1 5.5 9.1 13.2 9.1 23c0 8.8-4.1 17.4-12.2 25.9l-9.8 9.6l-.3.3c-2.9 3.4-4.6 8-5.2 13.9c-.2 2-1.9 3.6-4 3.6h6.9c2 0 3.8-1.6 4-3.6c.5-5.9 2.3-10.5 5.2-13.9l.3-.3l9.8-9.6c8.2-8.5 12.2-17.1 12.2-25.9c-.1-9.8-3.1-17.5-9.1-23");
}

.rss8zpbnq {
  fill: var(--svg-color--c33, #c33);
  d: path("M46.1 24.3c-2.1 2-3.4 4.4-4 7.4c-.3 1.9-2 3.2-3.9 3.2h6.9c1.9 0 3.6-1.3 3.9-3.2c.5-3 1.9-5.4 4-7.4q3.15-2.85 7.8-3.6c-1.1-.2-2.3-.3-3.5-.3c-4.6.1-8.3 1.4-11.2 3.9");
}

.y2w3b8bvc {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M64.2 85c.5-5.9 2.3-10.5 5.2-13.9l.3-.3l9.8-9.6c8.2-8.5 12.2-17.1 12.2-25.9c0-9.8-3-17.5-9.1-23C77.2 7.4 70 4.7 60.8 4.2c-8.9.5-16.2 3.3-21.9 8.2c-5.3 4.6-8.5 10.6-9.4 18.1c-.3 2.4 1.6 4.4 4 4.4h4.8c1.9 0 3.6-1.3 3.9-3.2c.5-3 1.9-5.4 4-7.4c2.8-2.6 6.6-3.9 11.2-3.9c1.2 0 2.4.1 3.5.3c1.1-.2 2.2-.3 3.4-.3c4.8 0 8.5 1.3 11 4s3.8 6.5 3.8 11.5c0 3.8-1.1 7.4-3.2 10.6c-1.4 2.2-4.7 5.8-10 10.9c-5.2 5.1-8.8 9.8-10.5 14c-1.4 3.4-2.3 7.7-2.5 12.9c-.1 2.3 1.7 4.2 4 4.2h3.5c1.8.1 3.6-1.5 3.8-3.5");
}

</style>
