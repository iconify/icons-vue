<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b6jnkibms"/><path class="ess-ukmyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ply" /></template>
<style>
.b6jnkibms {
  fill: var(--svg-color--8dd9f6, #8dd9f6);
  d: path("M13.687 19.299a7.313 7.313 0 1 0 0-14.625a7.313 7.313 0 0 0 0 14.625");
}

.ess-ukmyw {
  fill: var(--svg-color--6161f6, #6161f6);
  d: path("M14.88 13.371a1.688 1.688 0 0 0-.015-2.885l-9.31-5.582C4.43 4.229 3 5.039 3 6.35v11.3c0 1.32 1.446 2.128 2.57 1.438z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
