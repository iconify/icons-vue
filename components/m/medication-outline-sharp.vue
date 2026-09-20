<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl4mjha5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:medication-outline-sharp" /></template>
<style>
.zl4mjha5a {
  fill: currentColor;
  d: path("M11.385 16.5h1.23V14h2.5v-1.23h-2.5v-2.5h-1.23v2.5h-2.5V14h2.5zM6 19.885v-13h12v13zm1-1h10v-11H7zm-.538-13.77v-1h11.077v1zM7 7.886v11z");
}

</style>
