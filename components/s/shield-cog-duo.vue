<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0xrppfrs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/t/tv4sijtxc.css';
import '../../css/c/cj57dzbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x0xrppfrs"/><g class="dt0cm9dhy primary"><path class="j2vbli9go"/><path class="tv4sijtxc"/><path class="cj57dzbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-cog-duo" /></template>
