<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aktqz_bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:timer-12-filled" /></template>
<style>
.aktqz_bab {
  fill: currentColor;
  d: path("M3.5 0a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM1 6.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0m4 1a.5.5 0 0 0 1 0v-3a.5.5 0 0 0-1 0zm5.854-3.647a.5.5 0 0 1-.707.001l-1.002-.998a.5.5 0 1 1 .706-.708l1.002.998a.5.5 0 0 1 .001.707");
}

</style>
