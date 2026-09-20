<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="okr_tya5f"><path class="x45ajbl1j"/><path clip-rule="evenodd" class="u18o4acax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nabox" /></template>
<style>
.okr_tya5f {
  fill: var(--svg-color--2ac98b, #2ac98b);
}

.u18o4acax {
  fill-rule: evenodd;
  d: path("M12.5 21v-9l-8-4.75L12 3l8 4.5v9L17.5 18V9L15 10.5v9zm-3-13.75l2.5-1.5l3 1.75L12.5 9z");
}

.x45ajbl1j {
  d: path("m4 8l7.5 4.5V21L9 19.5v-6L6.5 12v6L4 16.5z");
}

</style>
