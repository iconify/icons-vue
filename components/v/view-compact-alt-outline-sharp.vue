<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkaimrbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-compact-alt-outline-sharp" /></template>
<style>
.jkaimrbhi {
  fill: currentColor;
  d: path("M7.5 16.5h4v-4h-4zm0-5h4v-4h-4zm5 5h4v-4h-4zm0-5h4v-4h-4zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
