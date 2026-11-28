<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjx1ls_pc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/agia-nwsy.css';
import '../../css/u/ug2_86nbt.css';
import '../../css/t/t5jm6bbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjx1ls_pc secondary"/><g class="dt0cm9dhy primary"><path class="agia-nwsy"/><path class="ug2_86nbt"/><path class="t5jm6bbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spider-duo" /></template>
