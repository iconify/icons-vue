<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxyqx31qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-hand-left-sharp" /></template>
<style>
.pxyqx31qc {
  fill: currentColor;
  d: path("m11.6 22l5.1-6.125l-3.3-3.3l-3.4 1.7V6H7V2h13v20zM7 22q-1.25 0-2.125-.875T4 19v-8l3-3h1v9.5l5-2.5l1 1l-4.4 5.275q-.275.35-.687.538T8.05 22zm7.213-15.288Q14.5 6.425 14.5 6t-.288-.712T13.5 5t-.712.288T12.5 6t.288.713T13.5 7t.713-.288");
}

</style>
