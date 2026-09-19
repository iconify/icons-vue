<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvj-fb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-currency-yen" /></template>
<style>
.dwvj-fb0f {
  fill: currentColor;
  d: path("M13.92 11H18v2h-5v2h5v2h-5v4h-2v-4H6v-2h5v-2H6v-2h4.08L5 3h2.37L12 10.29L16.63 3H19z");
}

</style>
