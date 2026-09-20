<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hy8g6htyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:navigation-play-20-regular" /></template>
<style>
.hy8g6htyw {
  fill: currentColor;
  d: path("M2.5 5a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zm0 5a.5.5 0 0 0 0 1h8.757c.313-.38.677-.716 1.08-1zm7.707 6a5.5 5.5 0 0 1-.185-1H2.5a.5.5 0 0 0 0 1zM20 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.287-.437l-2.97-1.65a.5.5 0 0 0-.743.437v3.3a.5.5 0 0 0 .743.437l2.97-1.65a.5.5 0 0 0 0-.874");
}

</style>
