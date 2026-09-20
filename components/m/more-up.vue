<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsc8gb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-up" /></template>
<style>
.ixsc8gb_e {
  fill: currentColor;
  d: path("M17 16V7H8V5h11v11zm-5 5v-9H3v-2h11v11z");
}

</style>
