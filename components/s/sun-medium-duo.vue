<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smr8-nmee.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/twr587btq.css';
import '../../css/m/m2aszhjda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary smr8-nmee"/><g class="dt0cm9dhy primary"><path class="twr587btq"/><path class="m2aszhjda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sun-medium-duo" /></template>
