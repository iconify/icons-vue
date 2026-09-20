<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<rect class="u40h-kb6a"/><path class="c2dpwgc_b"/><path class="dn5za55nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:middleman" /></template>
<style>
.c2dpwgc_b {
  fill-opacity: var(--svg-fill-opacity--0-35, 0.35);
  d: path("M118.096 189.197V68.219L88.675 72.35l-22.498 43.601l-21.382-38.41l-24.731 3.909v95.353l23.28 3.964v-60.35l22.777 42.931h.502L90.63 120.25v64.871zM19.561 53.983v12.505l108.864-18.032V32.489zm0 147.887l108.864 21.438v-15.911L19.56 189.308z");
}

.dn5za55nk {
  fill: var(--svg-color--fff, #fff);
  d: path("M128.425 32.49v15.966l108.864 18.032V53.983zm108.361 144.313V81.45l-24.731-3.908l-21.382 38.41l-22.5-43.602l-29.42-4.131v120.978l27.467-4.076v-64.87l24.006 43.097h.502l22.778-42.93v60.349zm-108.361 46.505l108.864-21.438v-12.562l-108.864 18.089z");
}

.u40h-kb6a {
  width: 256px;
  height: 256px;
  fill: var(--svg-color--f1c761, #f1c761);
  rx: 22px;
}

</style>
