<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctv276buq"/><path class="z3u-q355b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-connected-tv" /></template>
<style>
.ctv276buq {
  fill: currentColor;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v2h8v-2h4c1.1 0 1.99-.9 1.99-2L22 5c0-1.1-.9-2-2-2m0 14H4V5h16zM5 14v2h2c0-1.11-.89-2-2-2m0-3v1.43c1.97 0 3.57 1.6 3.57 3.57H10c0-2.76-2.24-5-5-5m0-3v1.45c3.61 0 6.55 2.93 6.55 6.55H13c0-4.42-3.59-8-8-8");
}

.z3u-q355b {
  fill: currentColor;
  d: path("M4 5h16v12H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
