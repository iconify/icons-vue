<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5csq_bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netshoes" /></template>
<style>
.z5csq_bbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 11.593l-3.287 14.742c-1.784 8.004-6.913 11.632-11.55 9.432C25.229 34.138 24.59 28.413 24 24s-1.23-10.138-4.663-11.767c-4.637-2.2-9.766 1.428-11.55 9.432L4.5 36.407");
}

</style>
