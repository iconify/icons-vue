<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv34jc3sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:square-small" /></template>
<style>
.iv34jc3sr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 6.25h3q1.76 0 3.005 1.245T17.75 10.5v3q0 1.76-1.245 3.005T13.5 17.75h-3q-1.76 0-3.005-1.245T6.25 13.5v-3q0-1.76 1.245-3.005T10.5 6.25");
}

</style>
