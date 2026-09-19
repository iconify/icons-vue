<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd-_8lt4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shyft" /></template>
<style>
.cd-_8lt4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 17.668l-9.543-9.543v6.231h-6.583a6.623 6.623 0 0 0-6.623 6.623h13.206v6.231zm-39 12.664l9.543 9.543v-6.231h6.583a6.623 6.623 0 0 0 6.624-6.623h0h-13.207V20.79z");
}

</style>
