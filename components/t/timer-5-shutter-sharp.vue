<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiyyuwygu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-5-shutter-sharp" /></template>
<style>
.kiyyuwygu {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H8V5h9v3h-6v2.5h6V19z");
}

</style>
