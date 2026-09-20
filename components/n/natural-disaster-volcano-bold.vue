<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxy3cpb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxy3cpb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:natural-disaster-volcano-bold" /></template>
