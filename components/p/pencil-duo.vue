<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ix49qzbxz.css';
import '../../css/j/jm-o6kx0w.css';
import '../../css/l/lqpi8na-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ix49qzbxz"/><path class="jm-o6kx0w wm-a"/><path class="lqpi8na-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-duo" /></template>
