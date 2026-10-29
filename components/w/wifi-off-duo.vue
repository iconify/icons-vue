<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mjaro1bfj.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/t/t1q1i-8uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mjaro1bfj"/><path class="qr4ochb5c wm-s"/><path class="t1q1i-8uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-off-duo" /></template>
