<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrx-whwks.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/ha4_9m1_p.css';
import '../../css/n/nyaxwelsj.css';
import '../../css/x/xgg-uc19w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrx-whwks secondary"/><g class="dt0cm9dhy primary"><path class="ha4_9m1_p"/><path class="nyaxwelsj"/><path class="xgg-uc19w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-sparkles-duo" /></template>
