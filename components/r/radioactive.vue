<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="phm49tbyx"/><circle class="fuv2j0i8a"/><g class="jeunsn1yj"><circle class="rlr_7ebtx"/><path class="zgnvlhbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:radioactive" /></template>
<style>
.fuv2j0i8a {
  cx: 32px;
  cy: 32px;
  r: 27px;
  fill: var(--svg-color--ffe62e, #ffe62e);
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.phm49tbyx {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.rlr_7ebtx {
  cx: 32px;
  cy: 32px;
  r: 5px;
}

.zgnvlhbis {
  d: path("M8 28.8L25.1 31c.2-1.9 1.2-3.5 2.7-4.6L17.3 12.6c-5 3.9-8.5 9.6-9.3 16.2m24 10c-.9 0-1.8-.2-2.7-.5l-6.6 15.9c2.9 1.2 6 1.9 9.3 1.9s6.4-.7 9.3-1.9l-6.6-15.9c-.9.3-1.8.5-2.7.5m6.9-7.8L56 28.8c-.8-6.6-4.3-12.3-9.3-16.1L36.2 26.4c1.4 1.1 2.4 2.7 2.7 4.6");
}

</style>
