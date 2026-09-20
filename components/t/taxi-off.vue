<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mweqpbcpj.css';
import '../../css/s/sti5_nikw.css';
import '../../css/e/ece434l3x.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mweqpbcpj"/><path clip-rule="evenodd" class="sti5_nikw"/><path clip-rule="evenodd" class="ece434l3x"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:taxi-off" /></template>
