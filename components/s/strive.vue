<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jlyultbfy"/><path class="w7qix-bfh"/><path class="cm3324bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:strive" /></template>
<style>
.cm3324bol {
  d: path("M24.862 42.5V17.96c0-.997.803-1.8 1.8-1.8h3.568c.998 0 1.8.803 1.8 1.8V42.5M11.429 31.901H8.86v-4.248h2.569m31.07 4.248H32.03m0-4.248H42.5");
}

.jlyultbfy {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.w7qix-bfh {
  d: path("M17.694 35.053c0 .997-.803 1.8-1.8 1.8h-2.665c-.997 0-1.8-.803-1.8-1.8V24.502c0-.998.803-1.8 1.8-1.8h2.665c.997 0 1.8.802 1.8 1.8m0 17.998V17.96c0-.997.803-1.8 1.8-1.8h3.568c.997 0 1.8.803 1.8 1.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
