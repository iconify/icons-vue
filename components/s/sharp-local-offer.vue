<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrlah3-kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-offer" /></template>
<style>
.vrlah3-kt {
  fill: currentColor;
  d: path("M22.83 12.99L11.83 2H2v9.83l10.99 10.99zM5.5 7C4.67 7 4 6.33 4 5.5S4.67 4 5.5 4S7 4.67 7 5.5S6.33 7 5.5 7");
}

</style>
