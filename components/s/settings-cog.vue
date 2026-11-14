<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3_97mbzw"/><path class="bnjnom5xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:settings-cog" /></template>
<style>
.bnjnom5xi {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.n3_97mbzw {
  d: path("m10.474 4.912l.261-2.327h2.53l.261 2.327l2.407.997l1.83-1.461l1.789 1.789l-1.461 1.83l.997 2.407l2.327.261v2.53l-2.327.261l-.997 2.407l1.461 1.83l-1.789 1.789l-1.83-1.461l-2.407.997l-.261 2.327h-2.53l-.261-2.327l-2.407-.997l-1.83 1.461l-1.789-1.789l1.461-1.83l-.997-2.407l-2.327-.261v-2.53l2.327-.261l.997-2.407l-1.461-1.83l1.789-1.789l1.83 1.461Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
