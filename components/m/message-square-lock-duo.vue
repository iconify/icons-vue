<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_aqibxi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dp12a2bii.css';
import '../../css/v/vrq2tu6vd.css';
import '../../css/c/c29jx0u_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sg_aqibxi"/><g class="dt0cm9dhy primary"><path class="dp12a2bii"/><path class="vrq2tu6vd"/><path class="c29jx0u_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-lock-duo" /></template>
