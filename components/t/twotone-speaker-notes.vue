<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg2u671mt"/><path class="dcpt7kb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-speaker-notes" /></template>
<style>
.dcpt7kb-o {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H5.17l-.59.59l-.58.58V4h16zM6 12h2v2H6zm0-3h2v2H6zm0-3h2v2H6zm4 6h5v2h-5zm0-3h8v2h-8zm0-3h8v2h-8z");
}

.fg2u671mt {
  fill: currentColor;
  d: path("m4 17.17l.59-.59l.58-.58H20V4H4zM10 6h8v2h-8zm0 3h8v2h-8zm0 3h5v2h-5zM6 6h2v2H6zm0 3h2v2H6zm0 3h2v2H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
