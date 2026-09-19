<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="pt7-rzbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myway" /></template>
<style>
.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.pt7-rzbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.637 19.561l-2.219 8.878l-2.22-8.878l-2.219 8.878l-2.22-8.878m-5.881 8.878l-2.22-8.878l-2.219 8.878l-2.22-8.878L8 28.439m14.759-8.878L19.819 24l-2.941-4.439m2.941 8.878V24M40 19.561L37.059 24l-2.941-4.439m2.941 8.878V24m-3.502 1.469H30.16m1.477-5.908l2.885 8.878");
}

</style>
