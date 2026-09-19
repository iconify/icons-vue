<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bluvotbgm"/><path class="utzor-jzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-card-travel" /></template>
<style>
.bluvotbgm {
  fill: currentColor;
  d: path("M4 17h16v2H4zm13-7h-2V8H9v2H7V8H4v6h16V8h-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.utzor-jzf {
  fill: currentColor;
  d: path("M20 6h-3V4c0-1.11-.89-2-2-2H9c-1.11 0-2 .89-2 2v2H4c-1.11 0-2 .89-2 2v11c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2M9 4h6v2H9zm11 15H4v-2h16zm0-5H4V8h3v2h2V8h6v2h2V8h3z");
}

</style>
