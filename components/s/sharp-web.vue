<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucrd7xb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-web" /></template>
<style>
.ucrd7xb-m {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 9h10.5v3.5H4zm0 5.5h10.5V18H4zM20 18h-3.5V9H20z");
}

</style>
