<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hi7fo5k4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skool" /></template>
<style>
.hi7fo5k4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m2.152 27.07c1.034.812 2.15 1.184 4.659 1.184h1.27c2.068 0 3.745-1.571 3.745-3.51s-1.677-3.51-3.745-3.51H15.04c-2.068 0-3.745-1.571-3.745-3.51s1.677-3.51 3.745-3.51h1.27c2.508 0 3.625.372 4.66 1.185m7.672 5.315l8.063 7.508m-11.327-4.47l10.256-9.546m-10.258-7.144v21.192");
}

</style>
