<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hij-t_s7i.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t7hlcbb-q.css';
import '../../css/a/a_sewubtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hij-t_s7i secondary"/><g class="dt0cm9dhy primary"><path class="t7hlcbb-q"/><path class="a_sewubtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:video-duo" /></template>
