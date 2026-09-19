<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3uhe2bpd"/><path class="t2mi0xb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-desktop-mac" /></template>
<style>
.q3uhe2bpd {
  fill: currentColor;
  d: path("M3 4h18v10H3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t2mi0xb7t {
  fill: currentColor;
  d: path("M21 2H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h7l-2 3v1h8v-1l-2-3h7c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 12H3V4h18z");
}

</style>
