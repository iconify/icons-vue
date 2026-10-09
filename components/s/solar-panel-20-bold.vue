<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs1iioq3v.css';
import '../../css/u/ujdtqrbjr.css';
import '../../css/t/t5fnm26xn.css';
import '../../css/d/d2qyootpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gs1iioq3v"/><path class="ujdtqrbjr"/><path class="t5fnm26xn"/><path class="d2qyootpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-20-bold" /></template>
