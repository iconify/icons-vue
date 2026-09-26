<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ox7d0qb-k"/><path class="e89p18b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-end-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e89p18b1c {
  d: path("M13.5 12C13.5 12.8284 14.1716 13.5 15 13.5C15.8284 13.5 16.5 12.8284 16.5 12C16.5 11.1716 15.8284 10.5 15 10.5C14.1716 10.5 13.5 11.1716 13.5 12Z");
}

.ox7d0qb-k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3C2.7909 3 1 4.7909 1 7L1 17C1 19.2091 2.7909 21 5 21L14 21C14.7957 21 15.5587 20.6839 16.1213 20.1213L22.1213 14.1213C23.2929 12.9497 23.2929 11.0503 22.1213 9.8787L16.1213 3.8787C15.5587 3.3161 14.7957 3 14 3L5 3Z");
}

</style>
