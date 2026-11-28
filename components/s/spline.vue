<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/va5b0cwyk.css';
import '../../css/o/o4wz2ober.css';
import '../../css/j/jfa-fdaau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="va5b0cwyk"/><path class="o4wz2ober"/><path class="jfa-fdaau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spline" /></template>
