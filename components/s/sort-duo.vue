<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy6mvj7zt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rwdt3_bxc.css';
import '../../css/c/c7_ylbc_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy6mvj7zt secondary"/><g class="dt0cm9dhy primary"><path class="rwdt3_bxc"/><path class="c7_ylbc_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sort-duo" /></template>
