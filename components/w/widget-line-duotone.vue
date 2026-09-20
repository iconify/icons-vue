<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mj3osnb2a.css';
import '../../css/q/qu_g58izx.css';
import '../../css/l/lk2buz33l.css';
import '../../css/v/v382p5edm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mj3osnb2a"/><path class="qu_g58izx"/><path class="lk2buz33l"/><path class="v382p5edm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-line-duotone" /></template>
