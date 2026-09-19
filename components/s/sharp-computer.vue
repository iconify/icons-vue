<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc37yebvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-computer" /></template>
<style>
.lc37yebvl {
  fill: currentColor;
  d: path("m20 18l2-2V4H2v12l2 2H0v2h24v-2zM4 6h16v10H4z");
}

</style>
