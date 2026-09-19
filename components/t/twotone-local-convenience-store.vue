<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul9gx575e"/><path class="ajoibnbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-convenience-store" /></template>
<style>
.ajoibnbrm {
  fill: currentColor;
  d: path("M10 16h4v4h8V7h-3V4H5v3H2v13h8zm-2 0v2H4V9h3V6h10v3h3v9h-4v-4H8zm3-5H9v-1h2V7H8v1h2v1H8v3h3zm4 1h1V7h-1v2h-1V7h-1v3h2z");
}

.ul9gx575e {
  fill: currentColor;
  d: path("M14 14h2v4h4V9h-3V6H7v3H4v9h4v-4zm-1-7h1v2h1V7h1v5h-1v-2h-2zM8 9h2V8H8V7h3v3H9v1h2v1H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
