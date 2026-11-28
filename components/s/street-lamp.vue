<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hdhvzybvr.css';
import '../../css/i/i-ynbibxz.css';
import '../../css/u/ukw3gwlbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hdhvzybvr"/><path class="i-ynbibxz"/><path class="ukw3gwlbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:street-lamp" /></template>
