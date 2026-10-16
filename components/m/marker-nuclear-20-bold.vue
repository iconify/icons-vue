<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/r/ryog7pbwy.css';
import '../../css/n/nnxkvbcoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="ryog7pbwy"/><path class="nnxkvbcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-nuclear-20-bold" /></template>
