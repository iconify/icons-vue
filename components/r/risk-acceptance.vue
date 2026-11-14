<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ial3fxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-acceptance" /></template>
<style>
.d8ial3fxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.038 18.5H7.06q-.172 0-.343-.023q-.171-.022-.337-.067q-.167-.044-.326-.11t-.308-.153q-.149-.086-.286-.191t-.258-.227q-.121-.121-.226-.258t-.191-.286t-.151-.309q-.066-.159-.11-.325q-.045-.167-.067-.338t-.022-.343t.023-.343t.068-.337t.111-.325t.153-.308L9.23 6.91q.043-.074.091-.145t.1-.139t.109-.133t.117-.124q.061-.061.126-.117q.064-.057.132-.109t.14-.099q.071-.048.145-.091q.075-.043.152-.08t.156-.071t.16-.06q.081-.028.164-.05t.167-.039t.169-.027q.085-.012.171-.017q.085-.006.171-.006t.171.006q.086.005.171.017q.085.011.169.027q.084.017.167.039t.164.05t.16.06q.079.033.156.071t.152.08t.145.091q.072.047.14.099t.132.109q.065.056.126.117q.06.06.117.124q.057.065.109.133t.1.139t.091.145l4.44 7.647l.028.05M14.75 18l2 2L21 15.75");
}

</style>
