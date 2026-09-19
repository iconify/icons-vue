<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp745iu0f"/><path class="jlgxunb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-note-add" /></template>
<style>
.jlgxunb8p {
  fill: currentColor;
  d: path("M13 11h-2v3H8v2h3v3h2v-3h3v-2h-3zm1-9H6c-1.1 0-2 .9-2 2v16c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8zm4 18H6V4h7v5h5z");
}

.wp745iu0f {
  fill: currentColor;
  d: path("M13 4H6v16h12V9h-5zm3 10v2h-3v3h-2v-3H8v-2h3v-3h2v3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
