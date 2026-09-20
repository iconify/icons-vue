<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rddmtd02r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:triangular-ruler" /></template>
<style>
.rddmtd02r {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M35.106 33.172L2.828.894C1.273-.662 0-.135 0 2.065V32c0 2.2 1.8 4 4 4h29.935c2.2 0 2.727-1.272 1.171-2.828M16.967 28H10c-1.1 0-2-.9-2-2v-6.968c0-1.1.637-1.363 1.414-.586l8.139 8.14c.777.777.513 1.414-.586 1.414");
}

</style>
