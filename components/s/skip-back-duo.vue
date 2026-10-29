<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/szxsr-b0l.css';
import '../../css/b/bx0wdaclv.css';
import '../../css/y/y1_qhmb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="szxsr-b0l"/><path class="bx0wdaclv wm-a"/><path class="y1_qhmb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:skip-back-duo" /></template>
