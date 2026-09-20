<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lo7e36akk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sketch-logo-bold" /></template>
<style>
.lo7e36akk {
  fill: currentColor;
  d: path("m249 96.1l-56-64a12 12 0 0 0-9-4.1H72a12 12 0 0 0-9 4.1l-56 64a12 12 0 0 0 .26 16.09l112 120a12 12 0 0 0 17.54 0l112-120a12 12 0 0 0 .2-16.09M213.55 92H182l-30-40h26.55ZM71.88 116l21.19 53l-49.46-53Zm86.4 0L128 191.69L97.72 116ZM104 92l24-32l24 32Zm80.12 24h28.27l-49.46 53ZM77.45 52H104L74 92H42.45Z");
}

</style>
