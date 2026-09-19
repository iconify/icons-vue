<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pqitm7bqk.css';
import '../../css/u/u5xjt86lx.css';
import '../../css/r/rlo9g2qew.css';
import '../../css/i/ina5vcbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pqitm7bqk"/><circle class="u5xjt86lx"/><circle class="rlo9g2qew"/><path class="ina5vcbuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paint-board" /></template>
