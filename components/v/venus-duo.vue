<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsxp20g3o.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w_i6ns67x.css';
import '../../css/g/gl47k-but.css';
import '../../css/u/u62xewbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsxp20g3o secondary"/><g class="dt0cm9dhy primary"><path class="w_i6ns67x"/><path class="gl47k-but"/><path class="u62xewbdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:venus-duo" /></template>
