<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lpnxgyw7y.css';
import '../../css/h/h_u1fj4xc.css';
import '../../css/v/vf4566bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lpnxgyw7y"/><path class="h_u1fj4xc"/><path class="vf4566bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sprout" /></template>
