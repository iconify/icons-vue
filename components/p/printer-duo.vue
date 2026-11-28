<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-d14a6-i.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q6-yzqnbc.css';
import '../../css/t/t9k8-4bbd.css';
import '../../css/u/u2_1zacnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-d14a6-i secondary"/><g class="dt0cm9dhy primary"><path class="q6-yzqnbc"/><path class="t9k8-4bbd"/><path class="u2_1zacnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:printer-duo" /></template>
