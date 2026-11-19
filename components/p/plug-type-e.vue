<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/t/tjwg41mjf.css';
import '../../css/k/kx85uxbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m4l-9ybuj"/><path class="tjwg41mjf"/><circle class="kx85uxbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:plug-type-e" /></template>
