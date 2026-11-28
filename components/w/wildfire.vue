<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tlglmhb4u.css';
import '../../css/b/b8mpirbns.css';
import '../../css/f/f0ywp_bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tlglmhb4u"/><path class="b8mpirbns"/><path class="f0ywp_bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wildfire" /></template>
