<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6f0jichf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u50chrd7i.css';
import '../../css/u/u-5ljab_d.css';
import '../../css/u/uk5v5mblj.css';
import '../../css/i/iwkdp9bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v6f0jichf"/><g class="dt0cm9dhy primary"><path class="u50chrd7i"/><path class="u-5ljab_d"/><path class="uk5v5mblj"/><path class="iwkdp9bgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:three-fingers-duo" /></template>
