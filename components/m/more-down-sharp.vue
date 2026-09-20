<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njq-t5b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-down-sharp" /></template>
<style>
.njq-t5b9p {
  fill: currentColor;
  d: path("M5 19V8h2v9h9v2zm5-5V3h2v9h9v2z");
}

</style>
