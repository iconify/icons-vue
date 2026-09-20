<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt5j9ksrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:security-outline" /></template>
<style>
.rt5j9ksrx {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m0-1.062q2.425-.75 4.05-2.962T17.95 12H12V4.144L6 6.375v5.156q0 .194.05.469H12z");
}

</style>
