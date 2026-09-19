<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-1c9tiib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-brightness-auto" /></template>
<style>
.k-1c9tiib {
  fill: currentColor;
  d: path("M10.85 12.65h2.3L12 9zM20 8.69V4h-4.69L12 .69L8.69 4H4v4.69L.69 12L4 15.31V20h4.69L12 23.31L15.31 20H20v-4.69L23.31 12zM14.3 16l-.7-2h-3.2l-.7 2H7.8L11 7h2l3.2 9z");
}

</style>
