<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avy98-bgc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/inid0ebvq.css';
import '../../css/i/ivcfsdbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avy98-bgc secondary"/><g class="dt0cm9dhy primary"><path class="inid0ebvq"/><path class="ivcfsdbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-duo" /></template>
