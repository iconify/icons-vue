<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="quezxpb2f"/><path class="nx6mb0bpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nx6mb0bpv {
  d: path("M9.236 7.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.quezxpb2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.445 21.832a20 20 0 0 1-2.482-1.956C6.192 17.322 4.001 13.878 4 10a7.98 7.98 0 0 1 2.343-5.657A7.98 7.98 0 0 1 12 2a7.98 7.98 0 0 1 5.657 2.343A7.98 7.98 0 0 1 20 10c-.001 3.878-2.192 7.322-4.963 9.876a20 20 0 0 1-2.482 1.956a1 1 0 0 1-1.11 0");
}

</style>
