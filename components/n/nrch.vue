<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e9iq4zbmt"/><path class="vaqz12b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nrch" /></template>
<style>
.e9iq4zbmt {
  fill: var(--svg-color--00e9b3, #00e9b3);
  d: path("M7.822 10.071V4.884A1.896 1.896 0 0 1 9.737 3h10.94v1.33a1.95 1.95 0 0 1-1.966 1.884h-6.557a.47.47 0 0 0-.476.463v3.394h7.071v1.363a1.88 1.88 0 0 1-1.915 1.851H5.237a1.885 1.885 0 0 1-1.915-1.851V10.07z");
}

.ft5dv1b6b {
  fill: none;
}

.vaqz12b0m {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.679 15.215v2.006c0 .314.257.565.56.565h6.517a1.93 1.93 0 0 1 1.922 1.941V21H9.744a1.93 1.93 0 0 1-1.922-1.941v-3.844z");
}

</style>
