<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1s4p8b4k.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/u/u60vqdban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1s4p8b4k secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="u60vqdban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-circle-duo" /></template>
