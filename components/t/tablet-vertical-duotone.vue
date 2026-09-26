<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b7o0occka"/><path class="pqmzp41vs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-vertical-duotone" /></template>
<style>
.b7o0occka {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 23H17C19.2091 23 21 21.2091 21 19V5C21 2.7909 19.2091 1 17 1H7C4.7909 1 3 2.7909 3 5V19C3 21.2091 4.7909 23 7 23Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pqmzp41vs {
  d: path("M8.5 13.5C9.3284 13.5 10 12.8284 10 12C10 11.1716 9.3284 10.5 8.5 10.5C7.6716 10.5 7 11.1716 7 12C7 12.8284 7.6716 13.5 8.5 13.5Z");
}

</style>
