<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnun2klcg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zdu-dcbfe.css';
import '../../css/f/fon0b9_ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnun2klcg secondary"/><g class="dt0cm9dhy primary"><path class="zdu-dcbfe"/><path class="fon0b9_ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:milestone-duo" /></template>
