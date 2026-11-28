<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u87oa6srz.css';
import '../../css/o/oy50g1bab.css';
import '../../css/q/q0dt6ib3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="u87oa6srz"/><path class="oy50g1bab"/><path class="q0dt6ib3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shapes" /></template>
