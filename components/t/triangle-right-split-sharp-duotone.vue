<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rlrr9-byr"/><path class="td0ecj17e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-right-split-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rlrr9-byr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.293 2.293C20.579 2.007 21.009 1.921 21.383 2.076C21.756 2.231 22 2.596 22 3V21C22 21.552 21.552 22 21 22H3C2.596 22 2.231 21.756 2.076 21.383C1.921 21.009 2.007 20.579 2.293 20.293L20.293 2.293Z");
}

.td0ecj17e {
  d: path("M20.293 2.293C20.579 2.007 21.009 1.921 21.383 2.076C21.756 2.231 22 2.596 22 3V21C22 21.552 21.552 22 21 22H20.586L10.586 12L20.293 2.293Z");
}

</style>
