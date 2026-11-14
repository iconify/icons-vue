<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/z/z_1v53bxt.css';
import '../../css/z/z854mhbck.css';
import '../../css/a/amwr5jblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m4l-9ybuj"/><path class="z_1v53bxt"/><rect class="z854mhbck"/><path class="amwr5jblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:status-available" /></template>
