<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw9djmb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poco-community" /></template>
<style>
.tw9djmb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.208 20.125c1.387 0 2.503 1.145 2.503 2.567v2.616c0 1.422-1.116 2.567-2.503 2.567s-2.504-1.145-2.504-2.567v-2.616c0-1.422 1.117-2.567 2.504-2.567m-14.944 0c1.387 0 2.504 1.145 2.504 2.567v2.616c0 1.422-1.117 2.567-2.504 2.567s-2.503-1.145-2.503-2.567v-2.616c0-1.422 1.116-2.567 2.503-2.567m9.975 5.151v.032c0 1.418-1.12 2.567-2.503 2.567s-2.504-1.15-2.504-2.567v-2.616c0-1.418 1.121-2.567 2.504-2.567s2.503 1.15 2.503 2.567v.032m-19.95 5.15v-7.749h2.474c1.399 0 2.533 1.165 2.533 2.603c0 1.437-1.134 2.602-2.533 2.602H10.29M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

</style>
