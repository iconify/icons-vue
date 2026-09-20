<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx0q9zbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thermostat-carbon" /></template>
<style>
.bx0q9zbai {
  fill: currentColor;
  d: path("M11.238 21.875q-.363-.15-.663-.425L2.55 13.425q-.275-.3-.425-.663T1.975 12t.15-.775t.425-.65l8.025-8.025q.3-.3.663-.438T12 1.975t.775.138t.65.437l8.025 8.025q.3.275.438.65t.137.775t-.137.763t-.438.662l-8.025 8.025q-.275.275-.65.425t-.775.15t-.763-.15");
}

</style>
