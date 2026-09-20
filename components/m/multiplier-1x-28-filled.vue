<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wm8_0_btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:multiplier-1x-28-filled" /></template>
<style>
.wm8_0_btg {
  fill: currentColor;
  d: path("M12 9a1 1 0 0 0-1.857-.516l-.006.01q-.008.015-.03.047a10 10 0 0 1-.667.89c-.474.562-1.143 1.225-1.954 1.711a1 1 0 0 0 1.029 1.716A9 9 0 0 0 10 11.735V19a1 1 0 1 0 2 0zm3.707 5.293a1 1 0 0 0-1.414 1.414L15.586 17l-1.293 1.293a1 1 0 0 0 1.414 1.414L17 18.414l1.293 1.293a1 1 0 0 0 1.414-1.414L18.414 17l1.293-1.293a1 1 0 0 0-1.414-1.414L17 15.586z");
}

</style>
