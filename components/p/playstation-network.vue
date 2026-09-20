<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csa0j6xil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csa0j6xil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playstation-network" /></template>
