<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr1jw-bfg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c99v-pbvj.css';
import '../../css/r/rum0klbyg.css';
import '../../css/p/p57qaeh-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr1jw-bfg secondary"/><g class="dt0cm9dhy primary"><path class="c99v-pbvj"/><path class="rum0klbyg"/><path class="p57qaeh-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:volume-duo" /></template>
