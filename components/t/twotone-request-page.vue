<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciancablb"/><path class="rpmsubbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-request-page" /></template>
<style>
.ciancablb {
  fill: currentColor;
  d: path("M13.17 4H6v16h12V8.83zM15 11h-4v1h3c.55 0 1 .45 1 1v3c0 .55-.45 1-1 1h-1v1h-2v-1H9v-2h4v-1h-3c-.55 0-1-.45-1-1v-3c0-.55.45-1 1-1h1V8h2v1h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rpmsubbwt {
  fill: currentColor;
  d: path("M13.17 4L18 8.83V20H6V4zM14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zm1 9h-4v1h3c.55 0 1 .45 1 1v3c0 .55-.45 1-1 1h-1v1h-2v-1H9v-2h4v-1h-3c-.55 0-1-.45-1-1v-3c0-.55.45-1 1-1h1V8h2v1h2z");
}

</style>
