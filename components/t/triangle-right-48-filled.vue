<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ea_m71bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-right-48-filled" /></template>
<style>
.ea_m71bmv {
  fill: currentColor;
  d: path("M40.773 20.471c2.99 1.617 2.966 5.916-.041 7.5L11.23 43.503C8.4 44.994 5 42.942 5 39.744V8.255c0-3.22 3.44-5.27 6.272-3.738z");
}

</style>
