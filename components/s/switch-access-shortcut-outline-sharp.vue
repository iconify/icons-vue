<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0hmtsbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-access-shortcut-outline-sharp" /></template>
<style>
.t0hmtsbfa {
  fill: currentColor;
  d: path("M14.539 21.02q-2.752-1.162-4.376-3.614t-1.624-5.429q0-2.39 1.102-4.495Q10.742 5.377 12.7 4H8.462V3h6.077v6.077h-1V4.589q-1.887 1.217-2.944 3.17t-1.057 4.199q0 2.569 1.35 4.707t3.65 3.256z");
}

</style>
