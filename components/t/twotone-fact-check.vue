<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g01t-1cll"/><path class="fr-lmgbsw"/><path class="pa1m5cbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fact-check" /></template>
<style>
.fr-lmgbsw {
  fill: currentColor;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H4V5h16z");
}

.g01t-1cll {
  fill: currentColor;
  d: path("M4 19h16V5H4zm9.41-8.25l1.41 1.42L17.99 9l1.42 1.42L14.82 15L12 12.16zM5 7h5v2H5zm0 4h5v2H5zm0 4h5v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pa1m5cbwi {
  fill: currentColor;
  d: path("M19.41 10.42L17.99 9l-3.17 3.17l-1.41-1.42L12 12.16L14.82 15zM5 7h5v2H5zm0 4h5v2H5zm0 4h5v2H5z");
}

</style>
