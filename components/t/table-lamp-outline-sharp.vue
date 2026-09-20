<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbd_hhw6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-lamp-outline-sharp" /></template>
<style>
.wbd_hhw6n {
  fill: currentColor;
  d: path("M13 21v-2h8v2zM5.525 9H9V5H7.275zM16 18V7h-5v4H2.475l3.5-8H11v2h7v13zM5.525 9H9z");
}

</style>
