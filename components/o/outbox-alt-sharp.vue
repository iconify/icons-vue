<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akzrbcboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:outbox-alt-sharp" /></template>
<style>
.akzrbcboi {
  fill: currentColor;
  d: path("M7 16.539L16.577 12L7 7.462v3.215L11 12l-4 1.323zM4 20V4h16v16z");
}

</style>
