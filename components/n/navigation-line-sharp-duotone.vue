<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ukjg2jbft"/><path class="u6q_4tb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-line-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u6q_4tb7b {
  d: path("M13 1V7H11V1H13Z");
}

.ukjg2jbft {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.929 8.41C12.256 8.46 12.756 8.69 12.901 9L18.902 21.57C19.072 21.92 19.015 22.35 18.76 22.65C18.504 22.95 18.097 23.07 17.719 22.96L11.999 21.28L6.28 22.96C5.902 23.07 5.493 22.95 5.238 22.65C4.983 22.35 4.928 21.92 5.098 21.57L11.097 9C11.224 8.73 11.652 8.49 11.929 8.41Z");
}

</style>
