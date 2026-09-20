<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdxhwm0sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trending-down-sharp" /></template>
<style>
.fdxhwm0sm {
  fill: currentColor;
  d: path("M16 18v-2h2.6l-5.2-5.15l-4 4L2 7.4L3.4 6l6 6l4-4l6.6 6.6V12h2v6z");
}

</style>
