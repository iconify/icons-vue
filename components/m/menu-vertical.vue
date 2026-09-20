<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uotk91dww.css';
import '../../css/j/jo17u180x.css';
import '../../css/i/ib318w12k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="n1lsf0bnc"><circle class="uotk91dww"/><circle class="jo17u180x"/><circle class="ib318w12k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:menu-vertical" /></template>
