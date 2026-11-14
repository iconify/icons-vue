<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfqsoqb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-fruit" /></template>
<style>
.xfqsoqb8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.909 6.165q2.003-.818 4.078-.127l.019.007q4.813 1.75 3.225 8.125q-.605 2.81-2.345 4.876Q16.03 21.25 14 21.25q-.519 0-1.279-.304q-.49-.196-.721-.196t-.721.196q-.76.304-1.279.304q-2.03 0-3.886-2.204q-1.74-2.066-2.345-4.876q-1.588-6.375 3.225-8.125l.019-.007q2.207-.735 4.334.238q.431-2.584 2.781-3.927q.064-.037.134-.06q.07-.024.143-.033q.074-.009.147-.004q.074.005.145.024q.072.02.138.053t.124.078t.107.101t.085.12q.074.129.093.277t-.02.292t-.131.262q-.091.118-.221.192q-1.542.881-1.963 2.514");
}

</style>
