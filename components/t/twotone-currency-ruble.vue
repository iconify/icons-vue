<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e25chh61c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-currency-ruble" /></template>
<style>
.e25chh61c {
  fill: currentColor;
  d: path("M13.5 3H7v9H5v2h2v2H5v2h2v3h2v-3h4v-2H9v-2h4.5c3.04 0 5.5-2.46 5.5-5.5S16.54 3 13.5 3m0 9H9V5h4.5C15.43 5 17 6.57 17 8.5S15.43 12 13.5 12");
}

</style>
