<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s1j7zrb7e"/><path class="ge5m_ub4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ge5m_ub4c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20H4V4h16v9m0 0l-7 7m0 0v-7h7");
}

.s1j7zrb7e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 4h16v9l-.034.034q.01-.01.004-.022a.02.02 0 0 0-.018-.012H13v6.952a.02.02 0 0 0 .012.018q.013.006.022-.004L13 20H4Z");
}

</style>
