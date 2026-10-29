<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j0ggkhb1g.css';
import '../../css/d/d5_gd2mux.css';
import '../../css/y/yo87urbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j0ggkhb1g"/><path class="d5_gd2mux wm-a"/><path class="yo87urbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:martini-duo" /></template>
