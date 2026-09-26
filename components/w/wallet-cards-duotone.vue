<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xlcsfqbrl"/><path clip-rule="evenodd" class="u_e6txb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u_e6txb7i {
  fill-rule: evenodd;
  d: path("M5 3L19 3C21.2091 3 23 4.7909 23 7L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 7C1 4.7909 2.7909 3 5 3ZM3 8L3 12L5 12C5.5523 12 6 12.4477 6 13C6 14.1046 6.8954 15 8 15C9.1046 15 10 14.1046 10 13C10 12.4477 10.4477 12 11 12L21 12L21 8L3 8Z");
}

.xlcsfqbrl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8L21 8L21 12L11 12C10.4477 12 10 12.4477 10 13C10 14.1046 9.1046 15 8 15C6.8954 15 6 14.1046 6 13C6 12.4477 5.5523 12 5 12L3 12Z");
}

</style>
