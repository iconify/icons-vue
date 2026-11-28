<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s05lsoo0a.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d6z50yb1i.css';
import '../../css/c/c_8ts8c3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s05lsoo0a secondary"/><g class="dt0cm9dhy primary"><path class="d6z50yb1i"/><path class="c_8ts8c3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:smartphone-duo" /></template>
