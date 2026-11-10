<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kdgmo01uv"/><path class="ra4arsbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:perspective-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kdgmo01uv {
  d: path("M23 11V13H20V20.06C19.976 20.29 19.818 20.6 19.646 20.77C19.396 20.95 19.027 21.05 18.726 20.96L13 19.32V23H11V18.75L4.726 16.96C4.35 16.85 4.063 16.46 4 16.08V13H11V18.75L13 19.32V13H20V11H23Z");
}

.ra4arsbty {
  d: path("M13 1V5.26L18.79 4.02C19.085 3.96 19.394 4.03 19.629 4.22C19.863 4.41 20 4.7 20 5V11H13V5.26L11 5.69V11H4V13H1V11H4V8C4 7.53 4.329 7.12 4.79 7.02L11 5.69V1H13Z");
}

</style>
