<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jkdc9hz9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:material-square-icon" /></template>
<style>
.jkdc9hz9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.019 40.704h5.962l10.741-10.741v10.74H42.5v-21.48zM24 32.944l18.5-18.487v-7.16L24 25.783L5.5 7.296v33.408h4.778V19.222z");
}

</style>
