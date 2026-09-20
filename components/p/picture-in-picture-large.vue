<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6qedzbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-large" /></template>
<style>
.g6qedzbqk {
  fill: currentColor;
  d: path("M2 20v-2h18V4h2v14q0 .825-.587 1.413T20 20zm4-4V6h12v10z");
}

</style>
