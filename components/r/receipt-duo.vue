<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1g4t1k_d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/ht47y72rz.css';
import '../../css/l/lls52bcwg.css';
import '../../css/x/x-c9wobbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1g4t1k_d secondary"/><g class="dt0cm9dhy primary"><path class="ht47y72rz"/><path class="lls52bcwg"/><path class="x-c9wobbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:receipt-duo" /></template>
