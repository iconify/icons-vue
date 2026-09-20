<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gpp05bc7w"/><path class="xzenoybiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pill" /></template>
<style>
.gpp05bc7w {
  fill: var(--svg-color--bb1a34, #bb1a34);
  d: path("m33.207 19.773l-8.868-8.855L11.105 24.54l8.684 8.685l.001-.001A9.47 9.47 0 0 0 26.5 36c5.246 0 9.5-4.254 9.5-9.5a9.47 9.47 0 0 0-2.793-6.727");
}

.xzenoybiy {
  fill: var(--svg-color--fdcb58, #fdcb58);
  d: path("M15.921 2.513A9.45 9.45 0 0 0 9.5 0A9.5 9.5 0 0 0 0 9.5c0 2.479.958 4.73 2.514 6.421l-.014.014l8.605 8.605l13.234-13.622z");
}

</style>
