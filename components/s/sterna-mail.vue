<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pgrfo3g0l"/><path class="namzwubhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sterna-mail" /></template>
<style>
.namzwubhg {
  d: path("M20.872 23.332c-1.652-2.49-9.665-4.624-17.335-2.907m23.866 3.081c1.222-2.988 10.545-4.789 17.097-3.198m-23.628 3.256l.772 8.43l2.672-5.871l2.255 5.64l.831-8.082");
}

.pgrfo3g0l {
  d: path("M3.5 20.198c5.368-4.039 10.3-5.837 20.575-2.144C34.56 14.195 39.388 16.3 44.5 20.134");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
