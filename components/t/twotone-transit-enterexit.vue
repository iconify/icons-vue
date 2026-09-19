<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc__3tt6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-transit-enterexit" /></template>
<style>
.uc__3tt6c {
  fill: currentColor;
  d: path("M15.98 6L9 12.77V8H6v10h10v-3h-4.85L18 8.03z");
}

</style>
