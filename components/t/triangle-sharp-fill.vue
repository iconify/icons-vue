<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_yh4f3zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-sharp-fill" /></template>
<style>
.g_yh4f3zn {
  fill: currentColor;
  d: path("M11.1258 2.5144C11.5068 1.8285 12.4932 1.8285 12.8742 2.5144L22.8742 20.5144C23.2445 21.1809 22.7625 22 22 22L2 22C1.2375 22 0.7555 21.1809 1.1258 20.5144L11.1258 2.5144Z");
}

</style>
