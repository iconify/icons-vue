<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4_eihb_d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dv5gz4bfo.css';
import '../../css/i/i77jj_b8u.css';
import '../../css/q/qqfouabbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4_eihb_d secondary"/><g class="dt0cm9dhy primary"><path class="dv5gz4bfo"/><path class="i77jj_b8u"/><path class="qqfouabbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shower-duo" /></template>
