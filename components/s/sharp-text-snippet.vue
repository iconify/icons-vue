<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_rucz0wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-text-snippet" /></template>
<style>
.k_rucz0wp {
  fill: currentColor;
  d: path("m21 9l-6-6H3v18h18zM7 7h7v2H7zm10 10H7v-2h10zm0-4H7v-2h10z");
}

</style>
