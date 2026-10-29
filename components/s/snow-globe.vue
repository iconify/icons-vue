<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pcxdo28jt.css';
import '../../css/i/iz8w4e7ux.css';
import '../../css/f/folfl_fvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pcxdo28jt"/><path class="iz8w4e7ux"/><path class="folfl_fvi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snow-globe" /></template>
