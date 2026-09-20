<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir19iab8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monorail-sharp" /></template>
<style>
.ir19iab8p {
  fill: currentColor;
  d: path("M11.5 17.173h1V20h4.654v1H6.866v-1H11.5zM8.23 3h7.54q1.332 0 2.281.949T19 6.231v9.173q0 1.191-.828 2.009t-1.999.818h-1.904v-2.827H9.731v2.827H7.827q-1.191 0-2.01-.818T5 15.403V6.232q0-1.333.932-2.282T8.23 3M6 6.77v3.769h12v-3.77z");
}

</style>
