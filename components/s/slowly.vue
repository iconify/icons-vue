<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gu-4a4vtg"/><path class="s3_4mebvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slowly" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gu-4a4vtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.5v-31m-4.36 16.88c-1.4 0-1.4-3.324-2.8-3.324s-1.4 3.324-2.801 3.324c-1.403 0-1.403-3.324-2.805-3.324c-1.401 0-1.401 3.324-2.802 3.324c-1.404 0-1.404-3.324-2.807-3.324c-1.407 0-1.407 3.324-2.813 3.324a.8.8 0 0 1-.272-.045m17.1 7.105c-1.4 0-1.4-3.324-2.8-3.324s-1.4 3.324-2.801 3.324c-1.403 0-1.403-3.324-2.805-3.324c-1.401 0-1.401 3.324-2.802 3.324c-1.404 0-1.404-3.324-2.807-3.324c-.93 0-1.246 1.455-1.76 2.44M19.64 39.5c-1.4 0-1.4-3.324-2.8-3.324s-1.4 3.324-2.8 3.324c-1.403 0-1.403-3.324-2.805-3.324c-1.212 0-1.376 2.487-2.304 3.159m21.067-25.837h9v9h-9z");
}

.s3_4mebvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.946 20.076a2.12 2.12 0 0 0 1.552.422h.423a1.25 1.25 0 0 0 1.247-1.25a1.25 1.25 0 0 0-1.247-1.25h-.847a1.25 1.25 0 0 1-1.247-1.25a1.25 1.25 0 0 1 1.247-1.25h.424a2.12 2.12 0 0 1 1.551.422");
}

</style>
