<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="au56fjbwo"/><path class="i8se2cclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pelisbox" /></template>
<style>
.au56fjbwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 28v2c0 2.216-1.784 4-4 4h-27c-2.216 0-4-1.784-4-4V18c0-2.216 1.784-4 4-4h27c2.216 0 4 1.784 4 4v2m-4-2.038l8 12.076m0-12.076l-8 12.076");
}

.i8se2cclv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.33 24a3.019 3.019 0 1 1 0 6.038h-4.981V17.963h4.981a3.019 3.019 0 1 1 0 6.038zm0 0h-4.975m16.57-6.038za4 4 0 0 1 4 4v4.075a4 4 0 0 1-8 0v-4.075a4 4 0 0 1 4-4");
}

</style>
