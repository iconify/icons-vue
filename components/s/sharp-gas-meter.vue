<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltez3eb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-gas-meter" /></template>
<style>
.ltez3eb8j {
  fill: currentColor;
  d: path("M20 4h-5V2h-2v2h-2V2H9v2H4v18h16zm-8 14c-1.38 0-2.5-1.1-2.5-2.46c0-1.09.43-1.39 2.5-3.79c2.05 2.38 2.5 2.7 2.5 3.79C14.5 16.9 13.38 18 12 18m4-8H8V8h8z");
}

</style>
