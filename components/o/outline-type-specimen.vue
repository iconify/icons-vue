<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5j_qdwkr"/><path class="fhr-abc5o"/><path class="a3lhhzblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-type-specimen" /></template>
<style>
.a3lhhzblf {
  fill: currentColor;
  d: path("M12.19 12.2h3.63l.8 2.3h1.56l-3.38-9h-1.6l-3.38 9h1.56zm1.77-5.03h.08l1.31 3.72h-2.69z");
}

.f5j_qdwkr {
  fill: currentColor;
  d: path("M4 6H2v14c0 1.1.9 2 2 2h14v-2H4z");
}

.fhr-abc5o {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12z");
}

</style>
