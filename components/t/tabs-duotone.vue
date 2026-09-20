<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="u2cbb1xjw"/><path class="g635f3r7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tabs-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g635f3r7y {
  d: path("M255.66 165.7a.2.2 0 0 0 0-.08L233.37 91.4A15.89 15.89 0 0 0 218.05 80H208a8 8 0 0 0 0 16h10.05l19.2 64H206l-20.63-68.6A15.89 15.89 0 0 0 170.05 80H160a8 8 0 0 0 0 16h10.05l19.2 64H158l-20.63-68.6A15.89 15.89 0 0 0 122.05 80H38a15.89 15.89 0 0 0-15.37 11.4L.37 165.6v.13A8.1 8.1 0 0 0 0 168a8 8 0 0 0 8 8h240a8 8 0 0 0 7.66-10.3M38 96h84.1l19.2 64H18.75Z");
}

.u2cbb1xjw {
  d: path("M152 168H8l22.29-74.3A8 8 0 0 1 38 88h84.1a8 8 0 0 1 7.66 5.7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
