<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwa3_zbyy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i_dg2gbxb.css';
import '../../css/c/co23gdcen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwa3_zbyy secondary"/><g class="dt0cm9dhy primary"><path class="i_dg2gbxb"/><path class="co23gdcen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:polaroid-duo" /></template>
