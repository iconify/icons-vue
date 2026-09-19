<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hki4sqbjq.css';
import '../../css/l/l5goj9tdn.css';
import '../../css/n/n-g5w935x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="hki4sqbjq"/><circle class="l5goj9tdn"/><circle class="n-g5w935x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:menu-meatball" /></template>
