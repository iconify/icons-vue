<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/v/v7y0zackt.css';
import '../../css/e/edk22ibmj.css';
import '../../css/a/aer981g6j.css';
import '../../css/z/zdy_qebhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="v7y0zackt"/><path class="edk22ibmj"/><path class="aer981g6j"/><path class="zdy_qebhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:translate" /></template>
