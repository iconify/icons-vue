<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m310abrnx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pyvr6bb5u.css';
import '../../css/a/aqep-bb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m310abrnx secondary"/><g class="dt0cm9dhy primary"><path class="pyvr6bb5u"/><path class="aqep-bb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mushroom-duo" /></template>
