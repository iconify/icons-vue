<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q7b6p55ew.css';
import '../../css/u/uxsptjbvt.css';
import '../../css/o/opi96xvus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q7b6p55ew"/><path class="uxsptjbvt wm-a"/><path class="opi96xvus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wine-duo" /></template>
