<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apafunidj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/q/qlgb7obud.css';
import '../../css/x/xtqu68bem.css';
import '../../css/d/d4tcmzeva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apafunidj secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="qlgb7obud"/><path class="xtqu68bem"/><path class="d4tcmzeva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thermostat-duo" /></template>
