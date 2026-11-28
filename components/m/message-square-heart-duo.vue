<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk3lszb2c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dp12a2bii.css';
import '../../css/n/nhr4esdiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xk3lszb2c"/><g class="dt0cm9dhy primary"><path class="dp12a2bii"/><path class="nhr4esdiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-heart-duo" /></template>
