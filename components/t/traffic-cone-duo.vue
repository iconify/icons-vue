<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htc6s5nmc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pqmz6enqv.css';
import '../../css/u/uu3b6qbsc.css';
import '../../css/o/o4mz_86wa.css';
import '../../css/v/vv4lo6b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htc6s5nmc secondary"/><g class="dt0cm9dhy primary"><path class="pqmz6enqv"/><path class="uu3b6qbsc"/><path class="o4mz_86wa"/><path class="vv4lo6b2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:traffic-cone-duo" /></template>
