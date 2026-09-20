<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lmgohkx2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-28-filled" /></template>
<style>
.lmgohkx2j {
  fill: currentColor;
  d: path("M13.75 2C7.26 2 2 7.26 2 13.75v.5C2 20.74 7.26 26 13.75 26h9.5A2.75 2.75 0 0 0 26 23.25v-9.5C26 7.26 20.74 2 14.25 2z");
}

</style>
