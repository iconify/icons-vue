<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_v_6zbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-fill" /></template>
<style>
.r_v_6zbbv {
  fill: currentColor;
  d: path("m3.106 7.553l1-2C4.643 4.478 5.652 3.001 7 3h10c1.348.001 2.357 1.478 2.894 2.553l1 1.999v.001c.07.139.106.292.106.447v10a3 3 0 0 1-3 3H6a3.004 3.004 0 0 1-3-3V8c0-.155.036-.308.106-.447M5 9v9a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9Zm3 6c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 18H9a1 1 0 0 1-1-1Zm2.586 1l3-3l-.586-.586l-3 3V16Z");
}

</style>
