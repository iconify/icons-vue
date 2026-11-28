<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq48_lb2l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n7r7azbdm.css';
import '../../css/o/ovrfz0-dn.css';
import '../../css/w/wj5b3pbsu.css';
import '../../css/e/eqibqh45w.css';
import '../../css/e/eybwu6b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq48_lb2l secondary"/><g class="dt0cm9dhy primary"><path class="n7r7azbdm"/><path class="ovrfz0-dn"/><path class="wj5b3pbsu"/><path class="eqibqh45w"/><path class="eybwu6b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:oven-duo" /></template>
