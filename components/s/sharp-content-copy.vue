<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj6xlccuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-content-copy" /></template>
<style>
.rj6xlccuw {
  fill: currentColor;
  d: path("M16 1H2v16h2V3h12zm5 4H6v18h15zm-2 16H8V7h11z");
}

</style>
