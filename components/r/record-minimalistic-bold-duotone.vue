<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3x_ug_ff.css';
import '../../css/t/tb35ynitm.css';
import '../../css/e/edwd7ibhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x_ug_ff"/><path class="tb35ynitm"/><path class="edwd7ibhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-bold-duotone" /></template>
