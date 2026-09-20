<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh0kuvzvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subscriptions-outline-sharp" /></template>
<style>
.bh0kuvzvj {
  fill: currentColor;
  d: path("M3 21V9h18v12zm1-1h16V10H4zm6.5-1.923L15.116 15L10.5 11.923zm-6-10.846v-1h15v1zm3-2.77v-1h9v1zM4 20V10z");
}

</style>
