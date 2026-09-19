<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcp43obvf"/><path class="iib8but1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-corporate-fare" /></template>
<style>
.iib8but1o {
  fill: currentColor;
  d: path("M12 7V3H2v18h20V7zm-2 12H4v-2h6zm0-4H4v-2h6zm0-4H4V9h6zm0-4H4V5h6zm10 12h-8V9h8zm-2-8h-4v2h4zm0 4h-4v2h4z");
}

.lcp43obvf {
  fill: currentColor;
  d: path("M10 19H4v-2h6zm0-4H4v-2h6zm0-4H4V9h6zm0-4H4V5h6zm10 12h-8V9h8zm-2-8h-4v2h4zm0 4h-4v2h4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
