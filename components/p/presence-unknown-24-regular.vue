<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ji4x-0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-unknown-24-regular" /></template>
<style>
.n9ji4x-0t {
  fill: currentColor;
  d: path("M12 3a9 9 0 1 0 0 18a9 9 0 0 0 0-18M0 12C0 5.373 5.373 0 12 0s12 5.373 12 12s-5.373 12-12 12S0 18.627 0 12");
}

</style>
