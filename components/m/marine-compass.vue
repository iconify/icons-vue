<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd_zjrbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marine-compass" /></template>
<style>
.yd_zjrbre {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.625 1.75h-3.25q-3.573 0-6.099 2.526T1.75 10.375v3.25q0 3.573 2.526 6.099t6.099 2.526h3.25q3.573 0 6.099-2.526t2.526-6.099v-3.25q0-3.573-2.526-6.099T13.625 1.75m1.634 9.83l-.759 2.552q-.214.719-.816 1.165l-2.139 1.586q-1.045.775-2.109.029t-.695-1.992l.759-2.552q.214-.719.816-1.165l2.139-1.586q1.045-.775 2.109-.029t.695 1.992");
}

</style>
