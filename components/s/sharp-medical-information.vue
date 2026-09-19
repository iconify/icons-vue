<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ti5bbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-medical-information" /></template>
<style>
.g0ti5bbkk {
  fill: currentColor;
  d: path("M22 7h-7V2H9v5H2v15h20zM11 4h2v5h-2zm0 12H9v2H7v-2H5v-2h2v-2h2v2h2zm2-1.5V13h6v1.5zm0 3V16h4v1.5z");
}

</style>
