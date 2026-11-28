<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub8_nm_uw.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fgbgd-38a.css';
import '../../css/v/vob1wqbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ub8_nm_uw"/><g class="dt0cm9dhy primary"><path class="fgbgd-38a"/><path class="vob1wqbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-haze-duo" /></template>
