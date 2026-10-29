<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rg8hszz0a.css';
import '../../css/d/d_tyvacbg.css';
import '../../css/t/tu5qhwb4p.css';
import '../../css/b/bqabc6niv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rg8hszz0a"/><path class="d_tyvacbg wm-a"/><path class="tu5qhwb4p"/><path class="bqabc6niv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scissors-duo" /></template>
