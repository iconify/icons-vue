<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4ualtbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-fill-sharp" /></template>
<style>
.e4ualtbzg {
  fill: currentColor;
  d: path("M8.051 2.377A1 1 0 0 1 9.833 3v3.667h2.5a1 1 0 0 1 .783 1.622l-5.833 7.334A1.002 1.002 0 0 1 5.5 15v-3.667H3a1 1 0 0 1-.783-1.622Zm9.93 6.427c.284 1.419 1.144 2.54 2.286 3.396a1 1 0 0 1 .107.093C21.65 13.57 22 15.253 22 17c0 1.33-.522 2.597-1.464 3.536a5.004 5.004 0 0 1-7.072 0A5 5 0 0 1 12 17c0-.544.081-1.09.272-1.601c.154-.41.377-.795.688-1.106a.999.999 0 0 1 1.707.707a.333.333 0 1 0 .666 0c0-.207-.017-.419-.083-.617c-.061-.179-.159-.348-.251-.513a12 12 0 0 1-.227-.423c-1.04-2.082-.078-3.882 1.603-5.228a1.002 1.002 0 0 1 1.606.585");
}

</style>
