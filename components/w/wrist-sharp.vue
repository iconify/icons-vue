<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8i_ni5lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wrist-sharp" /></template>
<style>
.z8i_ni5lj {
  fill: currentColor;
  d: path("M11 21.9L6.1 17H1V7h4.6l1.95-2H20v2h-6v1.5h8v2h-8V12h9v2h-9v1.5h7v2h-8.875l1.125 2.225z");
}

</style>
