<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpb32sb8l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/h/hkzg94bdk.css';
import '../../css/r/r23awsbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wpb32sb8l"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="hkzg94bdk"/><path class="r23awsbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-lock-duo" /></template>
