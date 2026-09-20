<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isacr0boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:step-over-sharp" /></template>
<style>
.isacr0boa {
  fill: currentColor;
  d: path("M9.875 18.125Q9 17.25 9 16t.875-2.125T12 13t2.125.875T15 16t-.875 2.125T12 19t-2.125-.875M4.075 12q.35-2.975 2.6-4.988T11.975 5q1.825 0 3.375.738T18 7.75V5h2v7h-7v-2h4.2q-.8-1.35-2.162-2.175T12 7Q9.8 7 8.125 8.425T6.1 12z");
}

</style>
