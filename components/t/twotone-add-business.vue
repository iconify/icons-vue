<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhs2o9i6f"/><path class="xh15btbto"/><path class="lxe7e-j4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-business" /></template>
<style>
.jhs2o9i6f {
  fill: currentColor;
  d: path("M15.36 9H3.64l-.6 3h12.92z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.lxe7e-j4d {
  fill: currentColor;
  d: path("M20 18v-3h-2v3h-3v2h3v3h2v-3h3v-2z");
}

.xh15btbto {
  fill: currentColor;
  d: path("M2 4h15v2H2zm13 13h2v-3h1v-2l-1-5H2l-1 5v2h1v6h9v-6h4zm-6 1H4v-4h5zm-5.96-6l.6-3h11.72l.6 3z");
}

</style>
