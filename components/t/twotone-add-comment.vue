<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5qovbgj"/><path class="qefq9-b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-comment" /></template>
<style>
.qefq9-b3l {
  fill: currentColor;
  d: path("M4 4v12h14.83L20 17.17V4zm13 7h-4v4h-2v-4H7V9h4V5h2v4h4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xg5qovbgj {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14l4 4V4c0-1.1-.9-2-2-2m0 15.17L18.83 16H4V4h16zM13 5h-2v4H7v2h4v4h2v-4h4V9h-4z");
}

</style>
