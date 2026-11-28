<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5160pbdf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f5ro_pbbz.css';
import '../../css/h/h6mtbcfpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5160pbdf secondary"/><g class="dt0cm9dhy primary"><path class="f5ro_pbbz"/><path class="h6mtbcfpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pin-duo" /></template>
