<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv1d4dbtm"/><path class="ff_j1_-hg"/><path class="t6z7jnqnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-door-front" /></template>
<style>
.ff_j1_-hg {
  fill: currentColor;
  d: path("M13 11h2v2h-2z");
}

.t6z7jnqnv {
  fill: currentColor;
  d: path("M19 19V5c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v14H3v2h18v-2zm-2 0H7V5h10z");
}

.xv1d4dbtm {
  fill: currentColor;
  d: path("M7 19h10V5H7zm6-8h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
