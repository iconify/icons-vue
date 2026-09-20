<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="comzuibwc"/><path class="dbjv49sau"/><path class="b7gkmc0xu"/><circle class="k6drk-bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:small-orange-diamond" /></template>
<style>
.b7gkmc0xu {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M59.82 48.04c-.5.4-11.7 11.5-11.7 11.5c-.5.42-.62 1.14-.3 1.7c.6.8 1.5.4 2 0s10.5-10.3 10.9-10.8c.41-.55.48-1.28.2-1.9a.7.7 0 0 0-.77-.62a.6.6 0 0 0-.33.12");
}

.comzuibwc {
  fill: var(--svg-color--f77e00, #f77e00);
  d: path("m65.72 44.04l18.5 18.4a2.73 2.73 0 0 1-.04 3.85c-.02.02-.04.04-.06.05l-18.4 18.6a2.837 2.837 0 0 1-4 0l-18.4-18.5a2.81 2.81 0 0 1-.1-3.9l18.5-18.4a2.74 2.74 0 0 1 3.88-.21c.05.03.08.07.12.11");
}

.dbjv49sau {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("m62.72 46.64l16.1 16.1c.91.95.88 2.45-.06 3.37c-.01.01-.02.02-.04.03l-16 16.2c-.92.97-2.45 1-3.42.08l-.08-.08l-16.1-16.1c-.97-.9-1.02-2.41-.12-3.38l.02-.02l16.2-16.1c.95-.98 2.5-1.02 3.5-.1");
}

.k6drk-bpo {
  cx: 46.62px;
  cy: 63.24px;
  r: 1.2px;
  fill: var(--svg-color--ffbd52, #ffbd52);
}

</style>
