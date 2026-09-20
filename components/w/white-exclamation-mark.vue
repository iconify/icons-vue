<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="fwgot-b6f"/><path class="gq5mj_c8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:white-exclamation-mark" /></template>
<style>
.fwgot-b6f {
  cx: 18px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.gq5mj_c8a {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M21 24a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0z");
}

</style>
