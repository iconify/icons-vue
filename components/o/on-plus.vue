<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tnff3ebem"/><path class="sf37-acjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:on-plus" /></template>
<style>
.sf37-acjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 18.413a6.95 6.95 0 0 1 3.248 5.898h0c0 3.826-3.059 6.926-6.83 6.926h0c-3.772 0-6.83-3.1-6.83-6.926a6.95 6.95 0 0 1 3.27-5.912M25.833 31.26V19.996c0-2.073 3.353-2.749 4.19-.47l3.784 10.302c.837 2.278 4.19 1.603 4.19-.471V18.096");
}

.tnff3ebem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-2.621 27.965v5.622m-2.813-2.811h5.622M16.517 15.453v6.15");
}

</style>
