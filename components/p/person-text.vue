<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5vzo1gnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-text" /></template>
<style>
.h5vzo1gnf {
  fill: currentColor;
  d: path("M17 18v-2h5v2zm-2-5v-2h7v2zm-2-5V6h9v2zm-7.125 3.125Q5 10.25 5 9t.875-2.125T8 6t2.125.875T11 9t-.875 2.125T8 12t-2.125-.875M2 18v-1.9q0-.525.25-1t.7-.75q1.125-.675 2.388-1.012T8 13t2.663.338t2.387 1.012q.45.275.7.75t.25 1V18z");
}

</style>
