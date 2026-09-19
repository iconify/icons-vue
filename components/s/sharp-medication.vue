<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs4rbm4dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-medication" /></template>
<style>
.hs4rbm4dn {
  fill: currentColor;
  d: path("M6 3h12v2H6zm13 3H5v15h14zm-3 9h-2.5v2.5h-3V15H8v-3h2.5V9.5h3V12H16z");
}

</style>
