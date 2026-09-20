<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nkc6r_byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netkeiba" /></template>
<style>
.nkc6r_byh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26 32.25h17.5l-19.5-14v-2.5l-10.583 7.466zm-8.192-5.881l5.692-4.016m-12.017 2.228L4.5 29.508v1.25l2.078 1.492H18.33l1.934-1.365z");
}

</style>
