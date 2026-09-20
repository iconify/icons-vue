<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvi26vgqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-wifi-bad" /></template>
<style>
.kvi26vgqe {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9l-2.475 2.475q-.575-.275-1.213-.413t-1.287-.137q-2.525 0-4.3 1.775T12.95 17q0 .65.138 1.288T13.5 19.5zm4.9-.5l-1.4-1.4l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.425 1.4l-2.1 2.1l2.075 2.1l-1.4 1.4l-2.1-2.075z");
}

</style>
