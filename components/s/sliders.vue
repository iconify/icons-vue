<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejokxacfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sliders" /></template>
<style>
.ejokxacfz {
  fill: currentColor;
  d: path("M5 14q-.846 0-1.423-.577T3 12t.577-1.423T5 10h14q.846 0 1.423.577T21 12t-.577 1.423T19 14zm9-1h5q.425 0 .713-.288T20 12t-.288-.712T19 11h-5z");
}

</style>
