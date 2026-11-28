<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl344es-n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oqqr_m9av.css';
import '../../css/z/ze9vub3ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl344es-n secondary"/><g class="dt0cm9dhy primary"><path class="oqqr_m9av"/><path class="ze9vub3ex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:panel-bottom-duo" /></template>
