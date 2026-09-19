<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nybederid"/><path class="f1ql6562x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:upwards-button" /></template>
<style>
.f1ql6562x {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.938 42.533c.194 2.843 1.437 5.216 3.137 6.257H50.01c1.704-1.045 2.95-3.426 3.139-6.272l-20.03-27.51l-20.18 27.525");
}

.nybederid {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.792 56.913a6.877 6.877 0 0 1-6.878 6.882H6.874A6.88 6.88 0 0 1 0 56.913V6.877A6.876 6.876 0 0 1 6.874 0h50.041a6.876 6.876 0 0 1 6.878 6.877z");
}

</style>
