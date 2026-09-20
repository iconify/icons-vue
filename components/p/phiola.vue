<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5rq72l8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phiola" /></template>
<style>
.o5rq72l8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.077 5.5c-2.162 1.246-10.976 21.022 5.804 23.09c16.946 2.09 18.256-7.974 18.256-10.498s.716-8.09-4.748-10.767c-5.883-2.88-9.63.172-9.63 2.408V42.5");
}

</style>
