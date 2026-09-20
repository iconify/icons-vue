<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irlawebhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-and-archive-outline" /></template>
<style>
.irlawebhf {
  fill: currentColor;
  d: path("m16.808 19.404l2.73-2.731l-.546-.546l-1.8 1.8v-4.1h-.769v4.1l-1.8-1.8l-.546.546zm-12.616-.865V5.384l12.281 5.25h-.07q-.451.039-.909.133t-.798.252L5.192 7v3.885L10.04 12l-4.847 1.116V17l6.035-2.57q-.123.287-.204.629q-.08.341-.1.576v.011zm9.78.912q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165m-8.78-5.02V7v10z");
}

</style>
