<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9bencb8t"/><path class="dbcmre8io"/><path class="y_5gu2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-cozy" /></template>
<style>
.dbcmre8io {
  fill: currentColor;
  d: path("M7.25 7.25h4v4h-4zm5.5 0h4v4h-4zm-5.5 5.5h4v4h-4zm5.5 0h4v4h-4z");
}

.w9bencb8t {
  fill: currentColor;
  d: path("M4 18h16V6H4zm8.75-10.75h4v4h-4zm0 5.5h4v4h-4zm-5.5-5.5h4v4h-4zm0 5.5h4v4h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y_5gu2b4c {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V6h16z");
}

</style>
