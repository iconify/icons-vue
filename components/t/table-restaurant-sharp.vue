<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-1o_wbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-restaurant-sharp" /></template>
<style>
.u-1o_wbwe {
  fill: currentColor;
  d: path("M16.8 11H7.225l-.275 2h10.1zM4 20l1.225-9h-3.55l2-7h16.65l2 7H18.8l1.2 9h-2l-.675-5H6.675L6 20z");
}

</style>
