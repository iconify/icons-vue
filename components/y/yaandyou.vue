<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ylf2i1eju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yaandyou" /></template>
<style>
.ylf2i1eju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.231 21.78h25.538M23.385 4.5h1.23c4.844 0 8.743 3.861 8.743 8.658v21.684c0 4.797-3.9 8.658-8.742 8.658h-1.231c-4.843 0-8.742-3.861-8.742-8.658V13.158c0-4.797 3.899-8.658 8.742-8.658");
}

</style>
