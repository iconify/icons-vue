<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4wbcpb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-payment" /></template>
<style>
.s4wbcpb6b {
  fill: currentColor;
  d: path("M22 4H2v16h20zm-2 14H4v-6h16zm0-10H4V6h16z");
}

</style>
