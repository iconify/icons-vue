<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l-l-zrb9o.css';
import '../../css/f/fqpodu9zv.css';
import '../../css/q/qjv_ievyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l-l-zrb9o"/><path class="fqpodu9zv wm-a"/><path class="qjv_ievyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paint-roller-duo" /></template>
