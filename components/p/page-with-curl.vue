<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vq5ty2b8h"/><path class="cofy1mbyv"/><path class="grkj56mrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:page-with-curl" /></template>
<style>
.cofy1mbyv {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M31 36H4c4 0 4-8 4-8a4 4 0 0 1 4-4h20c2.209 0 4 2 4 4c0 0 .25 8-5 8");
}

.grkj56mrc {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M24 7a1 1 0 0 1-1 1H5a1 1 0 0 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H5a1 1 0 0 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H5a1 1 0 0 1 0-2h18a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H5a1 1 0 1 1 0-2h18a1 1 0 0 1 1 1");
}

.vq5ty2b8h {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M28 32a4 4 0 0 1-4 4H4c-2.209 0-4-1.875-4-8V4a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4z");
}

</style>
